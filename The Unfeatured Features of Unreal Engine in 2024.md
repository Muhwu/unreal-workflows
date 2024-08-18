---
tags:
  - talk
  - unreal-fest
---
# Scene Construction
[1:10](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=70s) Environment Light Mixer - Quickly setup lights in a map
[1:53](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=113s) Cube Grid (Modelling tools) - Quick level design prototyping
[2:43](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=163s) Draw Spline Tool (Modelling tools) - Creates BP and modify spline
[3:39](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=219s) Landmass Erosion
[5:00](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=300s) RVT (Runtime Virtual Textures) - Smooth blend mesh in environment
[6:14](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=374s) Texture Variation Node - Break tiling texture in material
[6:41](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=401s) Landscape Physics Material Node - Custom fx for gn or different footstep sounds
[7:51](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=471s) Water System Overrides - Modify from project settings
[8:32](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=512s) Console Water Variables - VSM Filtering (Virtual Shadow Map)
[9:17](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=557s) Property Coloration Viewmode - Ctrl+Click on any property in details and it will grab all from the scene!
[10:10](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=610s) Render Resource Viewer - View what eats up the VRAM
[10:59](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=659s) Local Exposure - Blend between different exposures in the same view
[12:13](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=733s) Location Volume - Named markers for an area in map partition (Shared between team)
[13:15](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=795s) Use Pinning - Prevent actor from streaming out
[13:30](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=810s) Custom Filters - Regular expression used as filters
[14:02](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=842s) Source Control - In-engine source control
[15:04](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=904s) Diffing Selected - Not just blueprint, works on other asset types too
[15:17](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=917s) Diffing Selected - Use step to jump between changes
[15:43](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=943s) Diffing Selected - Lock and Unlock Panning/Zooming
[15:54](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=954s) Review Tool - Perforce only, Inspect specific changelist
[16:32](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=992s) Custom Validation - Setup in BP and C++ to prevent errors
# Working with Nanite
[17:34](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1054s) Nanite Tesselation - Off by default enabled using cvars
[18:48](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1128s) Nanite Landscape
[19:09](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1149s) Nanite Landscape Displacement
[19:50](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1190s) Nanite Vertex Color - Store data and reduce texture overhead
[20:53](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1253s) Nanite Spline Mesh - Spline Mesh Actor
[21:24](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1284s) Nanite Spline Mesh - 'Max Edge Length Factor'
[22:08](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1328s) Nanite Foliage 'Preserve Area' - Maintain visual consistency
[22:42](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1362s) Nanite Mesh can be controlled by WPO (World Position Offset)
[23:20](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1400s) Nanite setup troubleshooting WPO using 'Pixel Programmable Visualizer'
[24:14](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1454s) Nanite Overdraw mode
[25:20](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1520s) VSM Nanite Overdraw (Virtual Shadow Map)
[26:01](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1561s) Nanite Overrides - Selector in the material graph if mesh uses nanite
[26:30](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1590s) Nanite Overrides - Disallow nanite with translucent material
[26:45](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1605s) Level instances - Group nanite assets as placeable assemblies
[28:08](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1688s) Level instances - Actor Filters
[29:16](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1756s) Level instances - Easily break them to base actors
[29:47](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1787s) Level instances Zoo - Showcase your assets easily as they are instances
# PCG (Procedural Content Generation)
[30:10](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1810s) PCG Intro
[30:34](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1834s) PCG Data Asset Support - Convert level instance to PCG data assets
[31:58](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1918s) PCG Sample landscape layer data - Painting landscape layer and PCG filling it with rocks
[32:32](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=1952s) PCG Discard points on irregular surface
[33:23](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2003s) PCG Spline Water Data - Gets information from water system like stream speed
[33:52](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2032s) PCG Hierarchical Generation - Logic processed based on distance (PCG LOD?)
[33:35](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2015s) PCG Biomes Plugin
# Custom Tools
[37:15](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2235s) Interchange - Custom ruleset and import popup when importing certain assets
[37:46](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2266s) Geometry Scripts - Intro
[38:06](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2286s) Geometry Scripts Booleans - Cut holes in any mesh
[38:28](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2308s) Scriptable Tools Mode - Add your custom click, drag, etc.. tools
[38:57](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2337s) Toolbox Plugin - Custom button belt that does whatever you program
# Bells and Whistles
[40:10](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2410s) Animation Analysis - Works in blendspaces and sets values based on analysis rules
[40:58](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2458s) Harmonix Plugin - Create custom MIDI Sequences
[41:54](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2514s) Soundscape Plugin - Procedural audio in the environment without hand placing them
[42:29](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2549s) Data Channels - Detected by Niagara and spawns effects using one single Niagara asset
[43:07](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2587s) Niagara Simulation Stages - Output to Render Texture and do cool stuff
[43:40](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2620s) Niagara Caching - Caching to quickly play it back anytime later
[44:12](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2652s) Color Picker - Create your theme colors and save them (Can be shared between teams)
[44:53](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2693s) Translucency Overlay Material - Setup custom shadows using translucency pass
[45:22](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2722s) Post Process Material Chain Plugin - Output PP to RT to PP to... (RT = Render Targets) [46:15](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2775s) Slate Post Buffer - Render scene with UMG to texture
[47:00](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2820s) Console Variable Tool - Window > Console Variables and it shows all
[47:18](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2838s) ABTest - 'abtest' before any console command and it will alternate between them automatically
[47:42](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2862s) Use '?' in console command for description
[47:56](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2876s) Texture Graph - Create procedural textures inside Unreal
[48:21](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2901s) Data Flow - Sets geometry collection and ruleset for destructible objects
[48:52](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2932s) Physics Control Component - Add physics on top of existing animations
[49:13](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2953s) Cheat Manager
[49:38](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2978s) Blueprint C++ Header Preview - Generates C++ header based on blueprint
[49:56](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=2996s) Gameplay Tags - Can be used without GAS and it makes things easier
[50:48](https://www.youtube.com/watch?v=_BIZ3FOcLNs&t=3048s) Leet mode '-leet' - Run the project with this command and it replaces text with leet