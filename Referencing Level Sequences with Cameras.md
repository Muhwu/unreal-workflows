---
tags:
  - camera
  - sequencer
  - references
  - trouble-shooting
---
# Issue
When creating a [[Level Sequence]] with a cine camera in it, you might run into an issue where references to it break on engine start up. This is due to loading order of objects and can be circumvented by using soft references and loading them when the actor is constructed.
```
Assertion failed: InElementOwner [File:D:\build\++UE5\Sync\Engine\Source\Runtime\TypedElementFramework\Public\Elements\Framework\TypedElementOwnerStore.h] [Line: 131] Element owner passed to RegisterElementOwner was null for key (<GetTypedElementOwnerStoreKeyDebugString not implemented for key type>)! Element owners must be valid! UnrealEditor_Engine UnrealEditor_Engine UnrealEditor_CoreUObject UnrealEditor_CoreUObject UnrealEditor_CoreUObject UnrealEditor_CoreUObject UnrealEditor_CoreUObject UnrealEditor_Engine UnrealEditor_CinematicCamera
```
# Solution
The solution is to reference the [[Level Sequence]] through a **Soft Object Reference** or **TSoftObjectPtr**. This will allow the actual object to be loaded when needed.

Notice that this means you will have to handle the loading yourself. This can be done at any point either synchronously or asynchronously as long as it happens before you attempt to play the asset. One solution is to load them in the constructor of the object.
![[LoadLevelSequenceBlocking_Example.png]]
