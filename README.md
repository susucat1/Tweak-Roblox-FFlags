<h1 align="center">Tweak Roblox FFlags</h1>


![image](https://github.com/bloxstraplabs/bloxstrap/raw/main/Images/Bloxstrap-full-dark.png#gh-dark-mode-only)
# [Bloxstrap Download >>>>>](https://github.com/bloxstraplabs/bloxstrap/releases/)

![image](https://github.com/returnrqt/bloxstrap/raw/main/Images/Bloxstrap-full-dark.png#gh-dark-mode-only)
# [Fishtrap Download >>>>>](https://github.com/returnrqt/fishstrap/releases/)

![image](https://github.com/AppleBlox/appleblox/raw/main/.github/assets/logo.png)
# [AppleBlox (MacOS Only) Download >>>>>](https://github.com/AppleBlox/appleblox/tags)

> [!CAUTION]
> **Note!: Fast Flags are extremely powerful, being that they are intended to only be used by Roblox engineers. While they can be very useful, they can cause issues with stability and functionality if you don't know what you're doing.**

## How To Use BloxsTrap:
![newbie](http://web.archive.org/web/20240803170418im_/https://raw.githubusercontent.com/luafv/rbxflags/master/assets/tutorial260.gif)


<h1 align="center">Rendering API</h1>

### Direct X 11 🌟
```json
{
    "FFlagDebugGraphicsPreferD3D11": "true"
}
```

### Directx 11 Support BGRA
> [!NOTE]
> **Its still beta but its feature can help u smooth rendering and less lag frame**
```json
{
    "FFlagD3D11SupportBGRA": "true"
}
```

### Direct X 10 🌟
> [!NOTE]
> **FOR POTATO DESKTOP**
```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": "true",
    "FFlagGraphicsEnableD3D10Compute": "true",
    "FFlagRenderEnableGlobalInstancingD3D10": "true",
    "FFlagRenderEnableGlobalInstancingD3D11": "false"
}
```

### OpenGL 
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "true",
    "FFlagDebugGraphicsPreferOpenGL": "true",
    "FFlagGraphicsGLEnableHQShadersExclusion": "true",
    "FFlagGraphicsGLEnableSuperHQShadersExclusion": "true"
}
```

### Vulkan ❗
> [!CAUTION]
> **Note!: Visual Crashes**
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "true",
    "FFlagDebugGraphicsPreferVulkan": "true",
    "FFlagGraphicsVulkanBonusMemory": "true",
    "FFlagSupportHeadlessDeviceVulkan": "true",
    "FFlagRenderEnableGlobalInstancingVulkan": "true",
    "FFlagRenderEnableGlobalInstancingD3D11": "false"
}
```

### Allow GPU to use Vulkan even if buggy
```json
{
    "FStringVulkanBuggyRenderpassList": "YOUR_GPU"
}
```

### Metal ❗
> [!WARNING]
> **Note!: MacOS Only**
```json
{
    "FFlagDebugGraphicsPreferMetal": "true",
    "FFlagRenderEnableGlobalInstancingMetal": "true"
}
```

<h1 align="center">Lightning Technologies</h1>

### Voxel Lighting (Phase 1) 🌟
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
    "FFlagRenderUnifiedLighting12": "true"
}
```
<h1 align="center">Graphical Settings</h1>

### Stop Being Jumpscared
```json
{
    "DFFlagJumpScaresP2": "false"
}
```
### Custom Record Video Roblox 🌟
> [!NOTE]
> **Default = 30 FPS and 2M bit on 1 video 🤣🤣🤣**
```json
{
    "DFIntCaptureVideoMaxFrameRate": 60,
    "DFIntCaptureVideoBitrate": 8000000
}
```
### Quaternion Corrections Animations
> [!NOTE]
> **Applies quaternion-based corrections to character/object poses, helping ensure smoother and more accurate rotations, particularly during complex animations or movements.**
```json
{
    "FFlagQuaternionPoseCorrection": "true",
    "FFlagKeyframeSequenceUseRuntimeSyncPrims": "true"
}
```
### Multithreading Improvement 🌟
> [!NOTE]
> **Basically makes roblox use as many threads as u put there (+1 because of main/render thread) HOWEVER this is poorly made (L roblox) it actually just switches between the threads really quickly causing overhead**
> 
> **What i reccomend is setting this to 1 so it uses 2 worker threads + the main thread (wont go lower than this) if u have a decent cpu this can improve ur fps (it did for me)**
>
> **Default = 3**
```json
{
    "DFIntRuntimeConcurrency": "your core+1"
}
```
### Fast Preloading Everything 🌟
> [!NOTE]
> **This improves loading time speeds for games**
```json
{
    "DFFlagEnableMeshPreloading2": "true",
    "DFFlagEnableMeshPreloading": "true",
    "DFFlagEnableTexturePreloading": "true",
    "DFFlagEnableSoundPreloading": "true",
    "FFlagAssetPreloadingIXP": "true",
    "DFIntAssetPreloading": "9999999",
    "DFIntNumAssetsMaxToPreload": "9999999"
}
```
### Removes Only Roblox Texture 🌟
```json
{
    "FFlagTextureUseACR4": "true",
    "FFlagTexturePackUseACR4": "true",
    "FIntTextureUseACRHundredthPercent": "10000"
}
```
### Improved Object Detail Using Fractal Upsample
> [!NOTE]
> **FractalUpsample - Fractal upsampling is a technique used to increase the resolution or detail of an image, texture, or grid by applying fractal algorithms. Unlike traditional upscaling methods that simply stretch the original content, fractal upsampling generates new details based on mathematical fractal patterns. These patterns mimic natural complexity, allowing the upsampled image or grid to retain a more realistic or detailed appearance.**
```json
{
    "FFlagDebugGridForceFractalUpsample": "true"
}
```
### No Unaligned DXT
> [!NOTE]
> **DXT (also known as S3TC) is a texture compression format.
It’s widely supported on most GPUs and helps textures stay compressed while in video memory. This allows users to use more or larger textures. Unaligned DXT can cause performance issues on some low-end or unsupported GPUs.**
```json
{
    "FStringGraphicsDisableUnalignedDxtGPUNameBlacklist": "YOUR_GPU"
}
```
### Disable Frame Time Std Dev
> [!NOTE]
> **Default = True**
>
> **False = more smooth and less latency but i dont recommended ur use it in pvp/battleground game**
```json
{
    "DFFlagFrameTimeStdDev": "false"
}
```
### Configure FRM Refresh Rate 🌟
> [!NOTE]
> **60HZ or FPS Only**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "60",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "16",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "50"
}
```
> [!NOTE]
> **120HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "120",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "9",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "16"
}
```
> [!NOTE]
> **144HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "144",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "7",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "9"
}
```
> [!NOTE]
> **165HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "165",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "6",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "7"
}
```
> [!NOTE]
> **240HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "240",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "5",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "6"
}
```
> [!NOTE]
> **360HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "360",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "3",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "4"
}
```
> [!NOTE]
> **480HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "480",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "2",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "3"
}
```
> [!NOTE]
> **520HZ or FPS**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "520",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "2",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "2"
}
```
### Disable Render Shadow Huge Radius
```json
{
    "DFIntRenderShadowHugeRadius": "0"
}
```
### Fast Render
> [!WARNING]
> **More Laggy**
```json
{
     "FIntRenderFastCluster": "255"
}
```
### Render Mesh Optimize
```json
{
    "FIntRenderMeshOptimizeVertexBuffer": "1"
}
```
### Pixel Quality Roblox
> [!NOTE]
> **This flag makes your graphics pixelated, higher values will show you more pixels**
```json
{
    "DFIntDebugDynamicRenderKiloPixels": "1"
}
```
### Remove Rendering Pre Processor
```json
{
    "FFlagRemovedRbxRenderingPreProcessor": "true"
}
```
### Max Shadow Atlas Usage Before Downscale
> [!NOTE]
> **You can change number and work with Unified Lighting**
```json
{
    "FIntRenderMaxShadowAtlasUsageBeforeDownscale": "-1"
}
```
### Disable Highlights on Parts 🌟
```json
{
   "DFFlagRenderHighlightManagerPrepare": "true",
   "FFlagRenderHighlightManagerPrepare3": "true"
}
```
### Legacy Shadow
```json
{
   "FFlagRenderLegacyShadowsQualityRefactor": "true"
}
```
### SSAO (Screen-Space Ambient Occlusion)
```json
{
    "FFlagDebugSSAOForce": "true"
}
```
### Smoother Terrain ❗
> [!CAUTION]
> **The particle's speed is based on you FPS**
```json
{
    "FFlagRenderFixParticleDegenCrossProduct": "true",
    "FFlagDebugRenderingSetDeterministic": "true"
}
```
### Speed up particle emitters ❗
> [!CAUTION]
> **The particle's speed is based on you FPS**
``` json
{
    "FFlagRenderFixParticleDegenCrossProduct": "true",
    "FFlagDebugDeterministicParticles": "true"
}
```
### Threads
> [!NOTE]
> **You can use it or roblox default**
```json
{
    "FIntTaskSchedulerThreadMin": "0",
    "FIntRuntimeMaxNumOfThreads": "1800"
}
```
### HyperThreading 🌟
``` json
{
    "FFlagDebugCheckRenderThreading": "true",
    "FFlagRenderDebugCheckThreading2": "true"
}
```
### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
}
```
### Preserve rendering quality with display setting
```json
{
    "DFFlagDisableDPIScale": "true"
}
```
### Force Graphics Quality Level 
> [!NOTE]
> **Note: 1-21**
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```

### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels 🌟
> [!NOTE]
> **Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider**
```json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

### Low Render Distance
> [!NOTE]
> **Only Work if game have StreamingEnabled**
```json
{
    "DFIntDebugRestrictGCDistance": "1"
}
```
### FRM Levels
```json
Low

1 = 3
2 = 2
3 = 6

High

4 = 7
5 = 11
6 = 14
7 = 15 
8 = 17
9 = 18
10 = 21
```

### Disables fade in and fade out animation every light update
```json
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```

### Limits light updates
> [!NOTE]
> **You can use it or Roblox Default**
```json
{
    "FIntRenderLocalLightUpdatesMin": "0",
    "FIntRenderLocalLightUpdatesMax": "8"
}
```

### Disable PostFX
```json
{
    "FFlagDisablePostFx": "true"
}
```

### Force LOD on Meshes 🌟
> [!NOTE]
> **Not Recommend for Evade Player**
>
> **Weird Map**
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```
### White Everything
```json
{
    "FFlagSkyUseRGBEEncoding": "true"
}
```
### Black Wall
> [!CAUTION]
> **Very Buggy**
```json
{
    "FIntCameraFarZPlane": "60"
}
```
### Disable Feature Sky
```json
{
    "DFFlagThumbnailRestoreSky": "false",
    "FFlagAlwaysUseNewSkyRemovalBehavior": "false",
    "FFlagRenderSkyFixAvgIrradiance": "false",
    "FFlagUseSkyReadyState": "false"
}
```
### Gray Sky
> [!NOTE]
> **You can use it or Roblox Default**
```json
{
    "FFlagDebugSkyGray": "true"
}
```
### White Sky
> [!NOTE]
> **Only applies to games with the default skybox**
```json
{
    "FFlagRenderSkyFixAvgIrradiance": "false",
    "FFlagAlwaysUseNewSkyRemovalBehavior": "false",
    "FFlagDebugSkyGray": "true",
    "FFlagSkyUseRGBEEncoding": "true"
}
```
### Black Sky
> [!CAUTION]
> **Very Buggy**
```json
{
    "FFlagRenderSkyFixAvgIrradiance": "false",
    "FFlagAlwaysUseNewSkyRemovalBehavior": "false",
    "FFlagDebugSkyGray": "true",
    "FIntCameraFarZPlane": "600"
}
```
### Pause Voxelizer/Disable Baked Shadows
> [!WARNING]
> **If u play hornor game i dont recommend u use it**
```json
{
    "DFFlagDebugPauseVoxelizer": "true"
}
```
### Skip Mesh Voxelizer 🌟
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
> [!NOTE]
> **Combine with [Lighting Attenuation](https://FastFlags/FastFlags-Collective/?tab=readme-ov-file#lighting-attenuation) for better vision**
```json
{
    "FFlagFastGPULightCulling3": "true"
}
```
### Lighting Attenuation
> [!CAUTION]
> **Weird Lighting**
```json
{
    "FFlagNewLightAttenuation": "true"
}
```
### Frame Buffer 🌟
```json
{
    "DFIntMaxFrameBufferSize": "4",
    "FIntInterpolationAwareTargetTimeLerpHundredth": "100",
    "FIntMaquettesFrameRateBufferPercentage": "100",
    "DFIntMaxAverageFrameDelayExceedFactor": "0"
}
```
### Low Quallity Terrain Textures
> [!NOTE]
> **0 --> 4 for less quality 16, 32, 64 for higher quality**
```json
{
    "FIntTerrainArraySliceSize": "0"
}
```
### High Quality Textures 
> [!NOTE]
> **1 --> 3**
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
> [!NOTE]
> **1-4 Blurry, 5-7 low quality also removes studs, 8-10 Removes almost everything (this is better)**
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
### No Grass Motion
```json
{
    "FIntGrassMovementReducedMotionFactor": "0"
}
```
### Increased Grass Motion
```json
{
    "FIntGrassMovementReducedMotionFactor": "999"
}
```
### Force MSAA 
> [!NOTE]
> **1 --> 7**
```json
{
    "FIntDebugForceMSAASamples": "1"
}
```
### ShadowMap Bias 
> [!NOTE]
> **[Future & ShadowMap]***
```json
{
    "FIntRenderShadowmapBias": "-1"
}
```
### Disable Dynamic Heads Animations
> [!NOTE]
> **https://roblox.fandom.com/wiki/Dynamic_Head**
```json
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```
### Remove head roll limit for face tracking
> [!NOTE]
> **Server Sided Only**
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
### Quick game launch ❗
> [!CAUTION]
> **BUG cant loading fully item avatar**
``` json
{
    "FFlagEnableQuickGameLaunch": "true"
}
```
### Enable Highlight Outlines on any Rendering API ❗
> [!WARNING]
> **lag a bit use if u love highlight**
``` json
{
    "FFlagHighlightOutlinesOnMobile": "true"
}
```
### Enable Gpu Texture Compressor
``` json
{
    "FFlagRenderGpuTextureCompressor": "true"
}
```
### Enable HSR (Hidden Surface Removal) 🌟
> [!NOTE]
> **Its working like occlusion culling**
``` json
{
    "FFlagDebugForceGenerateHSR": "true",
    "FFlagHSRClusterImprovement": "true",
    "FFlagHSRRemoveDuplicateindices": "true",
    "FFlagDecodeHSROnLCThread": "true"
}
```
### Simulation Optimization Flag 🌟
##### Optimization, latency, delay FFlag
``` json
{
    "FFlagSimDcdEnableDelta2": "true",
    "FFlagSimDcdRefactorDelta3": "true",
    "DFIntBufferCompressionLevel": "0",
    "DFIntBufferCompressionThreshold": "100",
    "DFIntPerformanceControlFrameTimeMax": "1",
    "DFIntPerformanceControlFrameTimeMaxUtility": "-1",
    "FFlagPushFrameTimeToHarmony": "true",
    "DFIntAnimatorThrottleMaxFramesToSkip": "0",
    "DFIntNumFramesAllowedToBeAboveError": "0",
    "DFIntVisibilityCheckRayCastLimitPerFrame": "10",
    "DFIntNetworkSchemaCompressionRatio": "50",
    "DFIntTimeBetweenSendConnectionAttemptsMS": "50"
}
```
### Network Cpu RSS tweaks
``` json
{
    "DFIntPhysicsReceiveNumParallelTasks": "20",
    "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
    "FIntSimWorldTaskQueueParallelTasks": "20",
    "FIntSmoothClusterTaskQueueMaxParallelTasks": "20",
    "DFIntReplicationDataCacheNumParallelTasks": "20",
    "DFIntMegaReplicatorNumParallelTasks": "20"
}
```
### Unified Lighting Blend Zone
> [!WARNING]
> Smaller value = FPS boost > Bigger value = FPS loss
> 
> Explanation: Controls the distance over which light transitions blend.
> 
> Lower values create sharper transitions.
> 
> Higher values make transitions smoother.
``` json
{
     "FIntUnifiedLightingBlendZone": "400"
}
```
### Vertex Smoothing Group Tolerance
> [!WARNING]
> The FIntVertexSmoothingGroupTolerance flag controls the tolerance level for vertex smoothing groups in 3D graphics.
> 
> Lower values result in lower smoothing quality as more errors are tolerated, making models appear more angular and less smooth.
> 
> Higher values increase the smoothing accuracy, leading to smoother, more visually appealing models with fewer artifacts.
``` json
{
    "FIntVertexSmoothingGroupTolerance": "1000"
}
```
### Better shadows
> [!WARNING]
> **Loading will take longer but the shadows are much better**
``` json
{
    "FFlagRenderInitShadowmaps": "true"
}
```
### Raycast Performance Improvements 🌟
##### [Review](https://create.roblox.com/docs/workspace/raycasting)
> [!NOTE]
> **if u dont know just ignore it**
``` json
{
    "FFlagUserRaycastPerformanceImprovements": "true"
}
```
### Shoe Skip Render Mesh 🌟
```json
{
    "FFlagShoeSkipRenderMesh": "true"
}
```
### Enable Old ShaderLighting Roblox
```json
{
    "FFlagShaderLightingRefactor": "false"
}
```
### New Version of Render 🌟
##### Enables an updated rendering system to improve performance and manage render calls.
``` json
{
    "FFlagRenderCBRefactor2": "true"
}
```
### Directional Attenuation Max Points
> [!WARNING]
> Lower values: May improve performance but reduce lighting accuracy. > Higher values: Increase lighting accuracy at the cost of performance, potentially leading to slower rendering, especially in scenes with complex lighting setups.
> 
> Explanation: Limits the maximum number of sample points for calculating directional light attenuation.
> 
> Lower values improve performance but may reduce lighting accuracy.
> 
> Higher values increase lighting accuracy but may slow rendering in complex lighting setups.
``` json
{
    "FIntDirectionalAttenuationMaxPoints": "400"
}
```
### Simulation Optimization Flag 🌟
> [!NOTE]
> **Be mindful that while optimization can improve performance, it may also require testing to ensure that the behavior of sets remains consistent and that no necessary details are lost during the optimization process. The DFFlagSimOptimizeSetSize flag is used to optimize the size of sets in simulations. Enabling this flag activates optimization techniques that reduce the size of simulation sets, leading to better performance by decreasing memory usage and potentially improving processing speeds during simulations.**
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
##### [everything goes black on <3] ***[DFIntDebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/luafv/rbxflags/tree/master?tab=readme-ov-file#frm-levels) ]***
```json
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```
### Limits number of animations being played
```json
{
    "DFIntMaxActiveAnimationTracks": "0"
}
```
### Remove Bloom 🌟
``` json
{
    "FIntBloomFrmCutoff": "1654515",
    "FFlagRenderNoLowFrmBloom": "true"
}
```
### No Clouds/Sky 🌟
```json
{
    "FFlagRenderNoLowFrmBloom": "false",
    "FFlagFRMRefactor": "false"
}
```

<h1 align="center">Telemetry</h1>

### Disable Telemetry 🌟
```json
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "true",
    "FFlagDebugDisableTelemetryEphemeralStat": "true",
    "FFlagDebugDisableTelemetryEventIngest": "true",
    "FFlagDebugDisableTelemetryPoint": "true",
    "FFlagDebugDisableTelemetryV2Counter": "true",
    "FFlagDebugDisableTelemetryV2Event": "true",
    "FFlagDebugDisableTelemetryV2Stat": "true",
    "FFlagDisableMemoryTracking": "true",
    "FStringTencentAuthPath": "null"
}
```
### Disable In-game Advertisements 🌟
```json
{
    "FFlagAdServiceEnabled": "false"
}
```
### AdBlock In Roblox
```json
{
    "EnableNativeAdsProtocolAndroid3": "false",
    "NativeAdsProtocolRunInNewThread": "false",
    "FFlagAdServiceEnabled": "false",
    "DFFlagADS7645_RBXLOG_MIGRATION": false,
    "DFFlagAdServiceAccessMarketplaceServiceUnderDMLock": false,
    "DFFlagAdServiceCallErrorFunctionInsteadOfPrint": false,
    "DFFlagAdserviceFixRewardedVideoAdPlaySignalLog": false,
    "DFFlagAdServiceMoveVolumeChangedSignalHandlerToDmThread": false,
    "DFFlagAdsPreloadInteractivityAssets": false,
    "DFFlagOnDemandAdsProviderAccessAdServiceUnderDmLock": false,
    "FFlagAdServiceAdditionalDataModelChecksEnabled": false,
    "FFlagEnableRewardedVideoInAdService15": false,
    "FLogAdService": 0,
    "DFFlagEnableRewardedAdsSessionTrackingFields": false
}
```
### Disable In-Game Purchases
```json
{
    "DFFlagOrder66": "true"
}
```
### Disable Chat
```json
{
    "FFlagDebugForceChatDisabled": "true"
}
```
### Disable Voicechat
###### Setting this to True will not do anything 
###### [TIP] Use PlaceFilter for specific games
```json
{
    "DFFlagVoiceChat4": "false"
}
```
### Overlay that shows what you type
``` json
{
    "FFlagDebugTextBoxServiceShowOverlay": "true"
}
```
### Disable Bubble Chat
``` json
{
    "FFlagEnableBubbleChatFromChatService": "false"
}
```
### Disable Autocomplete
```json
{
    "FFlagEnableCommandAutocomplete": "false"
}
```

<h1 align="center">Quality of Life</h1>

### Unlimited FPS Unlocker
```json
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "false",
    "FFlagGameBasicSettingsFramerateCap5": "false",
    "DFIntTaskSchedulerTargetFps": "9999"
}
```
### GUI Hiding Toggles
```json
{
    "FFlagUserShowGuiHideToggles": "true",
    "FFlagGuiHidingApiSupport2": "true"
}
```
### Hide guis
Instructions: Replace "ID" with any group ID that you are in.
```json
{
    "DFIntCanHideGuiGroupId": "ID"
}
```
### Disable Fullscreen Title Bar
```json
{
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### Spammed letters
##### This fflag basically spams every other letter on roblox coregui and the game's gui but it doesn't affect some parts of the games!
##### Default is 0 and if you set it to anything higher it just follows whatever number you put
```json
{
    "FIntDebugTextElongationFactor": "999999"
}
```
### MTU
```json
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
```
### No Internet Disconnect
##### [You will still be kicked but the message wont show.]
```json
{
    "DFFlagDebugDisableTimeoutDisconnect": "true"
}
```
### Smoother/Faster Input 🌟
##### Tip: When enabled the game will use an updated implementation for processing user input, which may lead to smoother and more responsive interactions. This flag controls the refactoring of the legacy input handling system in Roblox.
##### Recommendation: Test your game thoroughly after enabling this flag to ensure that everything functions as expected.
``` json
{
    "FFlagLuaAppLegacyInputSettingRefactor": "true"
}
```
### Enable New Chat Report 🌟
``` json
{
    "DFFlagChatLineAbuseReportAPIEnabled2": "true"
}
```
### Disable Blue Button
```json
{
   "FFlagLuaAppEnableFoundationColors7": "false"
}
```
### Disable New Debug Menu UI
```json
{
    "FFlagImproveMicroprofilerReadability": "false"
}
```
### Stuttery Animation Fix
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
```
### Surf the web inside of Roblox
###### Click the Beta badge or the 13+ badge to open the webview browser.
```json
{
    "FFlagTopBarUseNewBadge": "true",
    "FStringTopBarBadgeLearnMoreLink": "https://google.com/",
    "FStringVoiceBetaBadgeLearnMoreLink": "https://google.com/"
}
```
### Adjust Default Timeout Time
###### 1 second = 1000
###### @dis_spencer
```json
{
    "DFIntDefaultTimeoutTimeMs": "10000"
}
```
### Automatically unmutes your mic on join (VC)
```json
{
    "FFlagDebugDefaultChannelStartMuted": "false"
}
```
### Lets you change the zoom out limit
###### Only applies to games that has not changed the default zoom limit
```json
{
    "FIntCameraMaxZoomDistance": "9999"
}
```
### Exclusive Fullscreen
```json
{
    "FFlagHandleAltEnterFullscreenManually": "false"
}
```
### Remove translated supported message on join
``` json
{
    "FFlagChatTranslationEnableSystemMessage": "false"
}
```
### Always display Render Stats
###### pretty self explanatory fflag, you can't disable them using the hotkey
```json
{
    "FFlagDebugAlwaysDisplayRenderStats": "true"
}
```
### Subscriptions Page
```json
{
    "FFlagLuaAppDevSubsEnabled": "true"
}
```
### Adjust Scroll Speed
```json
{
    "FIntScrollWheelDeltaAmount": "140"
}
```
### Capture posts
###### Twitter x Roblox edition
```json
{
    "FFlagCapturesPostEnabledForAll_v4": "true"
}
```
### Custom MicroProfiler Scale
```json
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
```

<h1 align="center">User Interface/Visuals</h1>

### Custom Disconnect Message
```json
{
    "FFlagReconnectDisabled": "true",
    "FStringReconnectDisabledReason": "You're stupid and I hate you"
}
```
### Verified Badge
```json
{
    "FStringWhitelistVerifiedUserId": "UserID"
}
```
### Verified Badge on everyone
```json
{
    "FFlagOverridePlayerVerifiedBadge": "true"
}
```
### Display FPS
```json
{
    "FFlagDebugDisplayFPS": "true"
}
```
### Applies rainbow colors to stuff
```json
{
    "FFlagDebugDisplayUnthemedInstances": "true"
}
```
### Revert new invite menu
```json
{
    "FFlagEnableNewInviteMenuIXP2": "false"
}
```
### Revert spacing on errors
```json
{
    "FFlagErrorPromptResizesHeight": "false"
}
```
### Remove Disconnect Blur/Loading Blur
```json
{
    "FIntRobloxGuiBlurIntensity": "0"
}
```
### Disable New Chat Translation Settings
```json
{
    "FFlagChatTranslationSettingEnabled3": "false"
}
```
### Enable New Camera Mode
``` json
{
    "FFlagNewCameraControls": "true"
}
```
### Disable CTM Climbing
```json
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "false"
}
```
### Disable Drag Detectors
```json
{
    "FFlagDragDetectors1": "false"
}
```
### Disable Feedback Button in ESC
```json
{
    "FFlagDisableFeedbackSoothsayerCheck": "false"
}
```
### Disable Camera & Selfview
``` json
{
    "FFlagSelfieViewEnabled": "true"
}
```
### Simple Preferred Text Size Scale 
##### Enables a font scaler in the escape menu
##### Found by Sky (364112742153584640) in Bloxstrap stuff
``` json
{
     "FFlagEnablePreferredTextSizeScale": "true",
     "FFlagEnablePreferredTextSizeSettingInMenus2": "true"
}
```
### Preferred Text Size Settings (Fully) 🌟
``` json
{
  "FFlagEnablePreferredTextSizeGuiService": "true",
  "FFlagEnablePreferredTextSizeScale": "true",
  "FFlagEnablePreferredTextSizeScalePerLayerCollector": "true",
  "FFlagEnablePreferredTextSizeSettingInMenus2": "true",
  "FFlagEnablePreferredTextSizeStyleFixesInCaptureMenu": "true",
  "FFlagEnablePreferredTextSizeStyleFixesInExperienceMenu": "true",
  "FFlagEnablePreferredTextSizeStyleFixesInPlayerList": "true",
  "FFlagPreferredTextSizeSettingBetaFeature": "true",
  "FIntPreferredTextSizeSettingBetaFeatureRolloutPercent": "100",
  "FFlagEnablePreferredTextSizeConnection": "true",
  "FFlagEnablePreferredTextSizeStyleFixesAddFriends": "true",
  "FFlagEnablePreferredTextSizeStyleFixesGameTile": "true",
  "FFlagEnablePreferredTextSizeStyleFixesInAppShell3": "true",
  "FFlagEnablePreferredTextSizeStyleFixesInPurchasePrompt": "true",
  "FFlagEnablePreferredTextSizeStyleFixesInReportMenu": "true"
}
```
### Disable Better Haptics
``` json
{
    "FFlagEnableBetterHapticsResultHandling": "false"
}
```
### New Report Menu
```json
{
    "FStringSelectInSceneReportMenuOverrideUserIds": "UserID"
}
```
### Removes the Experience Language option in settings
```json
{
    "FIntV1MenuLanguageSelectionFeaturePerMillageRollout": "0"
}
```
### Remove VC Beta Badge
```json
{
    "FFlagVoiceBetaBadge": "false",
    "FFlagTopBarUseNewBadge": "false",
    "FFlagBetaBadgeLearnMoreLinkFormview": "false",
    "FFlagControlBetaBadgeWithGuac": "false",
    "FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```
### VR Controller transparency
```json
{
    "FIntVRTouchControllerTransparency": "0"
}
```
### Disable VR Collision Fade
```json
{
    "FFlagViewCollisionFadeToBlackInVR": "false"
}
```
### Limit Videos Playing
```json
{
    "DFIntVideoMaxNumberOfVideosPlaying": "0"
}
```
### Disable DSA Reporting In-game
```json
{
    "FFlagDSAIllegalContentReporting2": "false"
}
```
### Desktop App Dev Tools
##### only works on web view windows like profiles, ctrl + shift + I
```json
{
    "FFlagDebugEnableNewWebView2DevTool": "true"
}
```
### Show All Error Strings
```json
{
    "FFlagDebugEnableErrorStringTesting": "true"
}
```
### Customize chat translation settings
```json
{
    "FStringChatTranslationEnabledLocales": "es_es,fr_fr,pt_br,de_de,it_it,ja_jp,ko_kr,id_id,tr_tr,zh_cn,zh_tw,th_th,pl_pl,vi_vn,ru_ru,"
}
```
### Remove the vr toggle
```json
{
    "FFlagAlwaysShowVRToggleV3": "false"
}
```
### Cleaner desktop home page 🌟
```json
{
    "FIntGameGridFlexFeedItemTileNumPerFeed": "0"
}
```
### Mini webview
```json
{
    "FFlagWebViewProtocol": "false"
}
```
### Remove Parental Controls Tab
```json
{
    "FFlagLuaAppsEnableParentalControlsTab": "false"
}
```
### Legacy Search
```json
{
    "FFlagAXSearchLandingPageIXPEnabled4": "false"
}
```
### Disable Profile Picture Customization
```json
{
    "FFlagAXDefaultAvatarToShopEnabled3": "false"
}
```
### old luaapp chat button
```json
{
    "FStringNewChatTabExperimentLayerValue": "2024MUSIC"
}
```
### Disable Toast Notifications
```json
{
    "FFlagToastNotificationsProtocolEnabled2": "false"
}
```
### Rename Communications to Voice Enabled
```json
{
    "FFlagGameDetailsDecoupledCommunication": "false"
}
```

<h1 align="center">User Interface/Visuals Experimental</h1>

### Disable centered experience details page 🌟
```json
{
    "FFlagLuaAppEdpSingleColumnIxp": "false"
}
```
### Dont Delay Surface App
```json
{
    "FFlagPerformanceControlDelaySingleSurfaceAppInit": "false"
}
```
### No opacity to Chrome UI
```json
{
    "FFlagChromeUsePreferredTransparency": "false"
}
```
### Multi Try On
##### Allows you to try on multiple things in the catalog and buy everything at once
```json
{
   "FFlagAXEnableMultiTryOnUI": "true"
}
```
### Reset Character instead of Respawn in Experience Menu
```json
{
    "FFlagInExperienceMenuResetButtonTextToRespawn": "false"
}
```
### Break Collectible Icon
```json
{
    "FFlagDisplayCollectiblesIcon": "false"
}
```
### Changes some tiny things about Party
```json
{
    "FFlagAppChatAddConnectUnibarForActiveSquad": "false"
}
```
### Renames Party back to Roblox Chat
```json
{
    "FFlagAppChatRebrandStringUpdates": "false"
}
```
### Disable Sidebar Text (Default: True)
```json
{
    "FFlagEnableNavBarLabels3": "false"
}
```
### Hide playerlist close button on Chrome UI
```json
{
    "FFlagDisablePlayerListDisplayCloseBtn": "true"
}
```
### Pin Chat on Chrome UI
```json
{
    "FFlagEnableChromePinnedChat": "true"
}
```
### Red font
###### You need to use Default Roblox Font to activate this. Also it can be glitchy in the settings menu
```json
{
    "FStringDebugHighlightSpecificFont": "rbxasset://fonts/families/BuilderSans.json"
}
```

<h1 align="center">Audio Related</h1>

### Enable Fmod Threading
```json
{
     "FFlagFmodUseRuntimeThreading4": "true"
}
```
### Voice chat range/volume
> [!NOTE]
> **For people that play Roblox on low volume, 10000 is the optimal range/volume but it's a personal opinion so adjust it to your liking and i hope this flag is useful**
```json
{
     "DFIntVoiceChatVolumeThousandths": "10000"
}
```
### Allows you to change voice chat distance 
###### default: [Min 7 Max 80]
```json
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```
### Sounds use physical velocity and become distorted
###### <2017
```json
{
    "FFlagSoundsUsePhysicalVelocity": "true"
}
```
### Audio Occlusion 🌟
```json
{
    "FFlagDebugEnableDirectAudioOcclusion2": "true"
}
```
### Limit audios that are being played
```json
{
    "DFIntMaxLoadableAudioChannelCount": "1"
}
```
### Mess with voice chat volume
###### default 1000
```json
{
    "DFIntVoiceChatVolumeThousandths": "100000"
}
```
### No sounds
```json
{
    "FFlagDebugRomarkMockingAudioDevices": "true"
}
```

<h1 align="center">Latency & Abuse</h1>

### Network Ownership
###### Better [Network Ownership](https://create.roblox.com/docs/physics/network-ownership) of parts
``` json
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000",
    "DFFlagDebugPhysicsSenderDoesNotShrinkSimRadius": "true",
    "FFlagDebugUseCustomSimRadius": "true"
}
```
### WIFI OPTIMIZE????
> [!WARNING]
> **Note!: if you want just use it. default 100**
``` json
{
    "DFIntTrackCountryRegionAPIHundredthsPercent": "10000"
}
```
### Walk Speed Scale Based
##### Taller characters have a slower walking animation.
``` json
{
    "DFFlagUserAnimateScaleRun ": "true"
}
```
### Keyboard Latency 🌟
##### Default value: 500 > > Lower value = more responsive keyboard.
##### This flag controls the keyboard input latency in milliseconds.By setting this value to 1, it minimizes the delay between key presses and the game's recognition of the input, effectively improving keyboard responsiveness. However, such a low value might cause excessively frequent key registration, which can lead to issues like repeated actions during key holds. The default value is 500 milliseconds, providing a balance between input responsiveness and preventing unintentional key repetition.
``` json
{
    "FIntActivatedCountTimerMSKeyboard": "100"
}
```
### Mouse Latency 🌟
##### Default value: 500 > > Lower value = more responsive mouse
##### This flag determines the mouse input delay in milliseconds. A lower value (such as 1) will reduce the latency between mouse movement or clicks and the game's response, making the mouse feel more responsive. However, setting the value too low could result in excessively sensitive mouse input, potentially leading to issues like unintended multiple clicks or overly sensitive pointer movements. The default value of 500 milliseconds provides a balance between responsiveness and control, reducing the risk of input errors.
``` json
{
    "FIntActivatedCountTimerMSMouse": "100"
}
```
### Gamepad Latency 🌟
##### Default value: 500 > > Lower value = more responsive gamepad
##### This flag determines the gamepad input delay in milliseconds. A lower value (such as 1) will reduce the latency between gamepad movement or button and the game's response, making the gamepad feel more responsive. However, setting the value too low could result in excessively sensitive gamepad input, potentially leading to issues like unintended multiple button or overly sensitive pointer movements. The default value of 500 milliseconds provides a balance between responsiveness and control, reducing the risk of input errors.
``` json
{
    "FIntActivatedCountTimerMSGamepad": "100"
}
```
### Touch Latency 🌟
##### Default value: 500 > > Lower value = more responsive touch
``` json
{
    "FIntActivatedCountTimerMSTouch": "100"
}
```
### Zero Delay with Mouse 🌟
##### Default value: 16 > > Lower value = more double click
``` json
{
    "FIntCLI20390_2": "0"
}
```
### Mesh Noclip V1
```json
{
    "DFIntPhysicsDecompForceUpgradeVersion": "1500"
}
```
### Mesh Noclip V2
```json

{
    "DFIntBulletContactBreakOrthogonalThresholdActivatePercent": 2147483647,
    "DFIntBulletContactBreakThresholdPercent": -2147483648,
    "DFIntBulletContactBreakOrthogonalThresholdPercent": -2147483648
}
```
### Mesh Noclip V3 (Combined)
```json
{
   "DFIntPhysicsDecompForceUpgradeVersion": "1500",
   "DFIntBulletContactBreakOrthogonalThresholdActivatePercent": 2147483647,
   "DFIntBulletContactBreakThresholdPercent": -2147483648,
   "DFIntBulletContactBreakOrthogonalThresholdPercent": -2147483648
}
```
### Better serversided character position
##### 100 makes your serversided character closer to your client
```json
{
    "DFIntS2PhysicsSenderRate": "100"
}
```
### Wall Glide
```json
{
    "DFIntMaximumUnstickForceInGs": "-10"
}
```
### Fling you or a part that is below you
```json
{
    "DFIntSolidFloorMassMultTenth": "-2147483647",
    "DFIntSolidFloorPercentForceApplication": "-450",
    "DFIntNonSolidFloorPercentForceApplication": "-3200"
}
```
### Fling Parts v2
```json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### Invisible 1 (Freezes you in place)
```json
{
    "DFIntGameNetOptimizeParallelPhysicsSendAssemblyBatch": "-1",
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "-1"
}
```
### Invisible 2 (restricts the client from moving through the server)
```json
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```
### Well known speed fflag (Buggy)
```json
{
    "DFIntMaximumUnstickForceInGs": "-1",
    "DFIntRaycastMaxDistance": "0"
}
```
### You dont have animations for the server but you do for your client
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Max raycast distance
##### breaks leg collision and some games under 3
```json
{
    "DFIntRaycastMaxDistance": "3"
}
```
### No animations
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### No knockback in certain games
##### In slap battles its bannable (USE AT YOUR OWN RISK)
```json
{
    "DFIntGameNetLocalSpaceMaxSendIndex": "100000",
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```
### Spin
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "true",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "true"
}
```
### Drive vehicles slow
```json
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```
### Drunk
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "true",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999"
}
```
### Even funnier drunk fflag
```json
{
    "DFIntMaxAltitudePDHipHeightPercent": "-10000",
    "DFIntNewPDAltitudeNoForceZonePercent": "14673",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999"
}
```
### Dev Console Logging
###### Changes how long a Message can be, doesn't give you the ability to exceed the 16k Message Length Limit
```Json
{
    "FIntStandardOutputMaximumCharacterLength": "1"
}
```
### Dev Console Log Count
###### Control how many developer console logs can be shown at once, for example if you set the limit to be 100, then 100 different log messages will be shown while any older ones will be deleted when the limit is reached
###### @satlybpro
``` json
{
    "FIntNewDevConsoleMaxLogCount": "2"
}
```
### Replace all Decals with a Test Image
###### @.rbx.bloxy
```json
{
    "FFlagDebugTestImageDrawItem": "true"
}
```
### Allows you to edit the DataModel Patch
```json
{
    "FFlagDataModelPatcherForceLocal": "true"
}
```
### Shows the state of a flag
```json
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
```
> [!TIP]
> 
```json
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```
### Useful for bladeball & deathball
```json
{
    "DFFlagPreventReturnOfElevatedPhysicsFPS": "false",
    "DFFlagReducePhysicsReceiverAllocations": "false",
    "DFIntPhysicsNOUCountHundredth": "2147483647"
}
```
