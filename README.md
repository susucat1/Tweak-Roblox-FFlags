<h1 align="center">Rendering API</h1>

### Direct X 11 🌟
```json
{
    "FFlagDebugGraphicsPreferD3D11": "true"
}
```

### Direct X 10
```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": "true",
    "FFlagGraphicsEnableD3D10Compute": "true"
}
```

### OpenGL
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "true",
    "FFlagDebugGraphicsPreferOpenGL": "true",
    "FFlagGraphicsGLEnableHQShadersExclusion": "true",
    "FFlagGraphicsGLEnableSuperHQShadersExclusion": "true",
    "FFlagGraphicsGLWindowsShutdownFix": "true"
}
```

### Vulkan❗
> [!CAUTION]
> **Note!: Visual Crashes with NVIDIA AND INTEL GPU work normal with AMD GPU**
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "true",
    "FFlagDebugGraphicsPreferVulkan": "true"
}
```

### Metal
###### MacOS Only
```json
{
    "FFlagDebugGraphicsPreferMetal": "true"
}
```

<h1 align="center">Lightning Technologies</h1>

### Voxel Lighting (Phase 1)
```json
{
    "DFFlagDebugRenderForceTechnologyVoxel": "true"
}
```

### Shadowmap Lighting (Phase 2)
```json
{
    "FFlagDebugForceFutureIsBrightPhase2": "true"
}
```

### Future Lighting (Phase 3)
```json
{
    "FFlagDebugForceFutureIsBrightPhase3": "true"
}
```

### Unified Lighting (LightGrid - Beta)
```json
{
    "FFlagRenderUnifiedLighting": "true"
}
```
<h1 align="center">Graphical Settings</h1>

### Dynamic Resolution Scale
```json
{
    "FFlagRenderDynamicResolutionScale11": "true"
}
```
### Rendering Pre Processor
```json
{
    "FFlagRemovedRbxRenderingPreProcessor": "true"
}
```
### Max Shadow Atlas Usage Before Downscale
> **Note!: u can change number and use unified lighting**
```json
{
    "FIntRenderMaxShadowAtlasUsageBeforeDownscale": "-1"
}
```
### Improve FPS and Smooth out your game
```json
{
    "DFIntTimestepArbiterDebounceFrames": "2147483647"
}
```
### More brighter
```json
{
    "FFlagRenderFixFog": "true"
}
```
### Smoother Terrain❗
> [!CAUTION]
> **Note!: The particle's speed is based on you FPS**
```json
{
    "FFlagDebugRenderingSetDeterministic": "true"
}
```
### Speed up particle emitters❗
> [!CAUTION]
> **Note!: The particle's speed is based on you FPS**
``` json
{
  "FFlagDebugDeterministicParticles": "true"
}
```
### Threads
> **Note!: You can use it or roblox default it**
```json
{
    "FIntTaskSchedulerThreadMin": "0",
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```
### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```

### Disable Shadows
> **Note!: Work only with Shadowmap Lighting**
```json
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647"
}
```

### Force Graphics Quality Level
> **Note!: 1-21**
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```

### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

### Low Render Distance
###### [FRM](https://github.com/luafv/rbxflags/tree/master?tab=readme-ov-file#frm-levels)
```json
{
    "DFIntDebugRestrictGCDistance": "1"
}
```

### Disables fade in and fade out animation every light update
```json
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```

### Limits light updates
```json
{
    "FIntRenderLocalLightUpdatesMin": "0",
    "FIntRenderLocalLightUpdatesMax": "10"
}
```

### Disable PostFX
```json
{
    "FFlagDisablePostFx": "true"
}
```

### Force LOD on Meshes
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```
### Gray Sky
###### Only applies to games with the default skybox
```json
{
    "FFlagDebugSkyGray": "true"
}
```
### Pause Voxelizer/Disable Baked Shadows
> **Note!: If u play hornor game i dont recommend u use it**
```json
{
    "DFFlagDebugPauseVoxelizer": "true"
}
```
### Skip Mesh Voxelizer
```json
{
    "DFFlagDebugSkipMeshVoxelizer": "true"
}
```
### Enable CPULightCulling
```json
{
    "FFlagDebugForceFSMCPULightCulling": "true"
}
```
### Enable GPULightCulling
###### Combine with [Lighting Attenuation](https://FastFlags/FastFlags-Collective/?tab=readme-ov-file#lighting-attenuation) for better vision
```json
{
    "FFlagFastGPULightCulling3": "true"
}
```
### Lighting Attenuation
> **Note!: BUG**
```json
{
    "FFlagNewLightAttenuation": "true"
}
```
### Frame Buffer
> **Note!: Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag**
```json
{
    "DFIntMaxFrameBufferSize": "4"
}
```
### Target Time & Frame Delay Performance
```json
{
    "FIntInterpolationAwareTargetTimeLerpHundredth": "100",
    "DFIntMaxAverageFrameDelayExceedFactor": "0"
}
```
### Low Quallity Terrain Textures
###### 4 for less quality 16, 32, 64 for higher quality
```json
{
    "FIntTerrainArraySliceSize": "0"
}
```
### High Quality Textures 
###### *[1-3]*
```json
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3"
}
```
### Lower Quality Textures
```json
{
    "DFIntPerformanceControlTextureQualityBestUtility": "-1"
}
```
### No avatar textures
```json
{
    "DFIntTextureCompositorActiveJobs": "0"
}
```
### Texture Manager
###### 1-4 Blurry, 5-7 low quality also removes studs, 8-10 Removes almost everything (this is better)
```json
{
    "FIntDebugTextureManagerSkipMips": "10"
}
```
### Remove Grass
```json
{
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0"
}
```
### Increased Grass Motion & No Grass Motion
###### Best for non gamers to touch grass
```json
{
    "FIntGrassMovementReducedMotionFactor": "0"
}
```
```json
{
    "FIntGrassMovementReducedMotionFactor": "999"
}
```
### Force MSAA 
###### *[1-7]*
```json
{
    "FIntDebugForceMSAASamples": "1"
}
```
### ShadowMap Bias 
###### ***[Future & ShadowMap]***
```json
{
    "FIntRenderShadowmapBias": "75"
}
```
### Faster preloading
``` json
{
    "DFIntNumAssetsMaxToPreload": "9999999"
}
```
### Reduce avatar item particles in first person
``` json
{
    "FFlagUserHideCharacterParticlesInFirstPerson": "true"
}
```
### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```json
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```
### Remove head roll limit for face tracking
###### server sided???
``` json
{
    "DFIntAvatarFaceChatHeadRollLimitDegrees": "360"
}
```
### Remove layered clothing related for searching in lua app catalog
```json
{
    "FStringAXCategories": "ClassicShirts.ClassicTShirts.ClassicPants"
}
```
### Quick game launch
> **Note!: BUG cant loading fully item avatar**
``` json
{
    "FFlagEnableQuickGameLaunch": "true"
}
```
### roblox shaders
##### false = old true  = new
``` json
{
    "FFlagShaderLightingRefactor": "true"
}
```
### Enable Highlight Outlines on any Rendering API
> **Note!: lag a bit use if u love highlight**
``` json
{
    "FFlagHighlightOutlinesOnMobile": "True"
}
```
### Simulation Optimization Flag
##### Optimization, latency, delay FFlag
``` json
{
    "FFlagSimEnableDCD16": "true",
    "DFIntBufferCompressionLevel": "0",
    "DFIntBufferCompressionThreshold": "100",
    "DFIntPerformanceControlFrameTimeMax": "1",
    "DFIntPerformanceControlFrameTimeMaxUtility": "-1",
    "FFlagPushFrameTimeToHarmony": "true",
    "FFlagUISUseLastFrameTimeInUpdateInputSignal": "true",
    "DFIntAnimatorThrottleMaxFramesToSkip": "1",
    "DFIntNumFramesAllowedToBeAboveError": "1",
    "DFIntVisibilityCheckRayCastLimitPerFrame": "10",
    "DFIntNetworkSchemaCompressionRatio": "100",
    "DFIntTimeBetweenSendConnectionAttemptsMS": "200"
}
```
### Unified Lighting Blend Zone
##### Smaller value = FPS boost > Bigger value = FPS loss
##### Explanation:
##### Controls the distance over which light transitions blend.
##### Lower values create sharper transitions.
##### Higher values make transitions smoother.
``` json
{
     "FIntUnifiedLightingBlendZone": "400"
}
```
### Vertex Smoothing Group Tolerance
##### The FIntVertexSmoothingGroupTolerance flag controls the tolerance level for vertex smoothing groups in 3D graphics.
##### Lower values result in lower smoothing quality as more errors are tolerated, making models appear more angular and less smooth.
##### Higher values increase the smoothing accuracy, leading to smoother, more visually appealing models with fewer artifacts.
``` json
{
    "FIntVertexSmoothingGroupTolerance": "1000"
}
```
### Better shadows
> **Note!: Loading will take longer but the shadows are much better**
``` json
{
    "FFlagRenderInitShadowmaps": "true"
}
```
### Raycast Performance Improvements
##### tip: Uses workspace:Raycast() instead of worldmodel:FindPartOnRayWithIgnoreList()
> **Note!: if u didnt know just dont use or google search**
``` json
{
    "FFlagUserRaycastPerformanceImprovements": "true"
}
```
### Render Occlusion Culling
##### [@CloneTrooper1019](https://x.com/MaximumADHD/status/1832331711486865769)
``` json
{
    "DFFlagUseVisBugChecks": "true",
    "FFlagEnableVisBugChecks": "true",
    "FFlagEnableVisBugChecks28": "true",
    "FFlagVisBugChecksThreadYield": "true"
}
```
### Move Pre-Render Phase [~25% Performance Boost]
###### This FastFlag moves the Pre-Render task to an off thread after all other tasks are completed. By default, Pre-Render runs first, forcing the render thread to wait until the Pre-Render process finishes before it can start rendering a frame.
###### With this FastFlag enabled, Pre-Renderer is executed while the main thread is processing the previous frame. This adjustment allows the main thread to proceed without waiting for Pre-Renderer, leading to increased framerates at the expense of some frame latency.
###### This flag is most effective in CPU-bound scenarios.
###### This fflag might cause issues
###### @blobanium
```json
{
    "FFlagMovePrerender": "true"
}
```
### New Version of Render
##### Enables an updated rendering system to improve performance and manage render calls.
``` json
{
  "FFlagRenderCBRefactor2": "true"
}
```
### Directional Attenuation Max Points
##### Tip: Lower values: May improve performance but reduce lighting accuracy. > Higher values: Increase lighting accuracy at the cost of performance, potentially leading to slower rendering, especially in scenes with complex lighting setups.
##### Explanation:
##### Limits the maximum number of sample points for calculating directional light attenuation..
##### Lower values improve performance but may reduce lighting accuracy.
##### Higher values increase lighting accuracy but may slow rendering in complex lighting setups.
``` json
{
   "FIntDirectionalAttenuationMaxPoints": "400"
}
```
### Simulation Optimization Flag
##### Be mindful that while optimization can improve performance, it may also require testing to ensure that the behavior of sets remains consistent and that no necessary details are lost during the optimization process. The DFFlagSimOptimizeSetSize flag is used to optimize the size of sets in simulations. Enabling this flag activates optimization techniques that reduce the size of simulation sets, leading to better performance by decreasing memory usage and potentially improving processing speeds during simulations.
``` json
{
  "DFFlagSimOptimizeSetSize": "true"
}
```
### Fully dark map
``` json
{
  "DFIntDebugFRMQualityLevelOverride": "1",
  "DFIntRenderClampRoughnessMax": "-640000000",
  "DFIntRenderClampRoughnessMin": "-640000000"
}
```
### Makes avatars shiny 
###### [everything goes black on <3] ***[DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/luafv/rbxflags/tree/master?tab=readme-ov-file#frm-levels) ]***
```json
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```
### Remove Bloom
``` json
{
  "FIntBloomFrmCutoff": "1654515",
  "FFlagRenderNoLowFrmBloom": "true"
}
```
### HyperThreading
``` json
{
    "FFlagDebugCheckRenderThreading": "true",
    "FFlagRenderDebugCheckThreading2": "true"
}
```
