## [[Looking For Check/Find FFlags] Join>>>>>>>](https://discord.gg/q5DYxgE4Bt)



> [!CAUTION]
> **Fast Flags are extremely powerful, being that they are intended to only be used by Roblox engineers. While they can be very useful, they can cause issues with stability and functionality if you don't know what you're doing.**



<h1 align="center">Rendering API</h1>



### Direct X 11
```json
{
    "FFlagDebugGraphicsPreferD3D11": "true"
}
```

### Direct X 10
> [!NOTE]
> **FOR POTATO WINDOWS**
```json
{
    "FFlagDebugGraphicsPreferD3D11FL10": "true",
    "FFlagGraphicsEnableD3D10Compute": "true",
    "FFlagRenderEnableGlobalInstancingD3D10": "true",
    "FFlagRenderEnableGlobalInstancingD3D11": "false"
}
```

### OpenGL
> [!NOTE]
> **Better with Android/Linux**
```json
{
    "FFlagDebugGraphicsPreferOpenGL": "true",
    "FFlagGraphicsGLEnableHQShadersExclusion": "true",
    "FFlagGraphicsGLEnableSuperHQShadersExclusion": "true"
}
```

### Vulkan
> [!WARNING]
> **Better with Android/Linux and MacOS**
```json
{
    "FFlagDebugGraphicsPreferVulkan": "true",
    "FFlagGraphicsVulkanBonusMemory": "true",
    "FFlagSupportHeadlessDeviceVulkan": "true",
    "FFlagRenderEnableGlobalInstancingVulkan": "true",
    "FFlagRenderEnableGlobalInstancingD3D11": "false"
}
```

### Allow Ur Old GPU Android
> [!NOTE]
> **if u didnt know u gpu [https://play.google.com/store/apps/details?id=flar2.devcheck]**
```json
{
    "FStringRenderIGGPUWhitelistAndroid": "YOUR_GPU"
}
```

### Allow GPU to use Vulkan even if buggy
```json
{
    "FStringVulkanBuggyRenderpassList2": "YOUR_GPU"
}
```

### Stabilizes Vulkan via memory telemetry 🌟
> [!NOTE]
> **Enables memory telemetry for Vulkan to help reduce crashes, bugs, and instability on Vulkan-based systems.**
```json
{
    "FFlagAllocatorVulkanMemoryTelemetry2": "true"
}
```

### No More Vulkan Blacklist
> [!NOTE]
> **Mostly for mobile devices**
```json
{
    "FStringGraphicsVulkanFutureGPUNameBlacklist": null,
    "FStringGraphicsVulkanPVRFutureDeviceBlacklist": null,
    "FStringGraphicsVulkanPVRFutureDriverBlacklist": null,
    "FStringGraphicsVulkanMaliFutureDeviceBlacklist": null,
    "FStringGraphicsVulkanMaliFutureDriverBlacklist": null,
    "FStringGraphicsVulkanAdrenoFutureDeviceBlacklist": null,
    "FStringGraphicsVulkanAdrenoFutureDriverBlacklist": null
}
```

### Metal
> [!WARNING]
> **MacOS Only**
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

### Feature VoxelGrid ❗
> [!CAUTION]
> **Visual Crashes & Buggy**
```json
{
    "FFlagVoxelGridNew6": "true"
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

### Disable Unified Lighting (LightGrid - Beta) 🌟
```json
{
    "FFlagRenderUnifiedLighting16": "false"
}
```

### Unified Lighting Blend Zone
``` json
{
     "FIntUnifiedLightingBlendZone": "400"
}
```



<h1 align="center">Graphical Settings</h1>



### Android Cpu Speed Method
> [!NOTE]
> **Can improve performance on some devices**
>
> **or worsen performance on some devices [this is very likely]**
```json
{
    "DFFlagNewAndroidCpuSpeedMethod": "true"
}
```

### Better Thumbnailer RGBA
```json
{
    "FFlagThumbnailerUseRGBA16": "true"
}
```

### Spatial Partition Optimization
> [!NOTE]
> **Control Roblox’s use of a split octree system for spatial partitioning, improving performance in managing 3D objects.**
```json
{
    "FFlagUseSplitOctree5": "true"
}
```

### Enable memory control predictor 🌟
> [!NOTE]
> **Activates a system that predicts low RAM and prevents crashes. Improves stability and performance on weak devices.**
```json
{
    "FFlagPerformanceControlLmkdPredictorEnabled6": "true"
}
```

### Stable Object Physics
> [!NOTE]
> **Prevents extreme/unrealistic object behavior by limiting inertia values during physics calculations.**
```json
{
    "DFFlagSimClampInertiaOnRead3": "true"
}
```

### New Large Replicators
```json
{
    "FFlagLargeReplicatorEnabled9": "true",
    "FFlagLargeReplicatorWrite5": "true",
    "FFlagLargeReplicatorRead5": "true",
    "FFlagLargeReplicatorSerializeRead3": "true",
    "FFlagLargeReplicatorSerializeWrite4": "true"
}
```

### Favor Performance Over Quality 🌟
```json
{
    "DFIntGraphicsOptimizationModePerformanceBiasPercent": 100,
    "FStringIXPGraphicsOptimizationModePerformanceBias": "performanceBias",
    "FStringIXPGraphicsOptimizationModeBalancedBias": "performanceBias",
    "FStringIXPGraphicsOptimizationModeQualityBias": "performanceBias"
}
```

### Alternative Runtime Algorithm 🌟
```json
{
    "FFlagTaskThreadUsesRuntime2": "true"
}
```

### Enable Performance Mode 🌟
```json
{
    "DFFlagDebugPerfMode": "true",
    "FFlagDebugPerfMode": "true",
    "DFFlagEnableIASPerfStats": "true"
}
```

### Optimize Collision Crash 🌟
```json
{
    "DFFlagOptimizeNoCollisionPrimitiveInMidphaseCrash": "true"
}
```

### New Framerate Performance System (Beta) 🌟
```json
{
    "FFlagEnableFPSAndFrameTime": "true"
}
```

### Reset Cache On Game Leave 🌟
> [!NOTE]
> **Clearing the cache can improve game performance, fix loading errors, and resolve connectivity problems.**
```json
{
    "FFlagResetCacheOnLeaveGame": "true",
    "FFlagClearCachedChannelOnLaunch": "true"
}
```

### Shapecasts
> [!NOTE]
> **https://devforum.roblox.com/t/introducing-shapecasts/2320655**
```json
{
    "DFIntShapecastMaxDistance": "1",
    "DFIntShapecastMaxSize": "1"
}
```

### Inverse Kinematics
> [!NOTE]
> **https://devforum.roblox.com/t/r15-inverse-kinematics-character/3555958**
```json
{
    "FFlagAnimationLodIkEnabled": "true",
    "DFFlagIkControlDeepProfile": "true",
    "DFFlagAnimatorPostProcessIK": "true",
    "DFFlagIkTwoBoneBetterSolver": "true",
    "DFFlagIKSolverValidateChain2": "true"
}
```

### Stop Being Jumpscared
```json
{
    "DFFlagJumpScaresP2": "false"
}
```

### Improved Object Detail
> [!NOTE]
> **FractalUpsample - Fractal upsampling is a technique used to increase the resolution or detail of an image, texture, or grid by applying fractal algorithms. Unlike traditional upscaling methods that simply stretch the original content, fractal upsampling generates new details based on mathematical fractal patterns. These patterns mimic natural complexity, allowing the upsampled image or grid to retain a more realistic or detailed appearance.**
```json
{
    "FFlagDebugGridForceFractalUpsample": "true",
    "DFFlagRenderLanczosUpsamplingNonRinging2": "true"
}
```

### Custom Record Video Roblox 🌟
> [!NOTE]
> **Default = 30 FPS and 2M bit**
```json
{
    "DFIntCaptureVideoMaxFrameRate": 60,
    "DFIntCaptureVideoBitrate": 8000000
}
```

### Quaternion Corrections Animations 🌟
> [!NOTE]
> **Applies quaternion-based corrections to character/object poses, helping ensure smoother and more accurate rotations, particularly during complex animations or movements.**
```json
{
    "FFlagKeyframeSequenceUseRuntimeSyncPrims": "true",
    "FFlagQuaternionPoseCorrection": "true"
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
    "DFFlagEnableMeshPreloading": "true",
    "DFFlagEnableTexturePreloading": "true",
    "DFFlagEnableSoundPreloading": "true",
    "FFlagAssetPreloadingIXP": "true",
    "DFIntAssetPreloading": "9999999",
    "DFIntNumAssetsMaxToPreload": "9999999"
}
```

### Preferred GPU 🌟
> [!NOTE]
> **Choose GPU u want use to play roblox**
```json
{
    "FStringDebugGraphicsPreferredGPUName": "YOUR_GPU"
}
```

### No Unaligned DXT 🌟
> [!NOTE]
> **DXT (also known as S3TC) is a texture compression format.
It’s widely supported on most GPUs and helps textures stay compressed while in video memory. This allows users to use more or larger textures. Unaligned DXT can cause performance issues on some low-end or unsupported GPUs.**
```json
{
    "FStringGraphicsDisableUnalignedDxtGPUNameBlacklist": "YOUR_GPU"
}
```

### Configure FRM Refresh Rate 🌟
> [!NOTE]
> **120Hz**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "120",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "12",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "18"
}
```
> [!NOTE]
> **144Hz**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "144",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "10",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "12"
}
```
> [!NOTE]
> **165Hz**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "165",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "8",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "10"
}
```
> [!NOTE]
> **180Hz**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "180",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "6",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "8"
}
```
> [!NOTE]
> **240Hz**
```json
{
    "DFIntGraphicsOptimizationModeFRMFrameRateTarget": "240",
    "DFIntGraphicsOptimizationModeMinFrameTimeTargetMs": "5",
    "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "6"
}
```

### Fast Render ❗
> [!WARNING]
> **More Laggy**
```json
{
     "FIntRenderFastCluster": "255"
}
```

### Fine Grain Culling 🌟
> [!NOTE]
> **Allows the system to remove objects more accurately, improving rendering efficiency.**
```json
{
    "FFlagFineGrainCull": "true"
}
```

### Disable Render Shadow Huge Radius
```json
{
    "DFIntRenderShadowHugeRadius": "0"
}
```

### Render Mesh Optimize
```json
{
    "FIntRenderMeshOptimizeVertexBuffer": "1"
}
```

### Pixel Quality Roblox 🌟
> [!NOTE]
> **144p = 37**
> 
> **240p = 77**
> 
> **360p = 230**
> 
> **480p = 410**
> 
> **720p = 922**
> 
> **1080p = 2074**
> 
> **1440p = 3686**
> 
> **2160p (4k) = 8294**
> 
> **4320p (8k) = 33178**
```json
{
    "DFIntDebugDynamicRenderKiloPixels": "922"
}
```

### Remove Rendering Pre Processor
```json
{
    "FFlagRemovedRbxRenderingPreProcessor": "true"
}
```

### Max Shadow Atlas Usage Before Downscale
```json
{
    "FIntRenderMaxShadowAtlasUsageBeforeDownscale": "-1"
}
```

### Disable Highlights on Parts 🌟
```json
{
    "DFFlagRenderHighlightManagerPrepare4": "true"
}
```

### Legacy Shadow 🌟
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
    "FFlagDebugRenderingSetDeterministic": "true"
}
```

### Speed up particle emitters ❗
> [!CAUTION]
> **The particle's speed is based on you FPS**
``` json
{
    "FFlagDebugDeterministicParticles": "true"
}
```

### Custom Threads
> [!NOTE]
> **You can use it or roblox default**
```json
{
    "FIntTaskSchedulerThreadMin": "0",
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```

### Fully Enable HyperThreading 🌟
``` json
{
    "FFlagDebugCheckRenderThreading": "true"
}
```

### Fully Enable MovePrerender ❗
> [!WARNING]
> **lag,stuttering = remove it**
```json
{
    "FFlagMovePrerender": "true"
}
```

### Preserve rendering quality with display setting
```json
{
    "DFFlagDisableDPIScale": "true"
}
```

### FRM Levels
```
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

### Force Graphics Quality Level 
> [!NOTE]
> **1 -> 21**
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```

### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels 🌟
> [!NOTE]
> **1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider**
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

### Disables fade in and fade out animation every light update
```json
{
    "FIntRenderLocalLightFadeInMs": "0"
}
```

### Custom Limits Light Updates
> [!NOTE]
> **You can use it or Roblox Default**
```json
{
    "FIntRenderLocalLightUpdatesMin": "0",
    "FIntRenderLocalLightUpdatesMax": "8"
}
```

### Disable Player Shadows
```json
{
    "FIntRenderShadowIntensity": "0"
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
> **Weird Map**
```json
{
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0"
}
```

### White Everything ❗
> [!CAUTION]
> **Cant See Anything**
```json
{
    "FFlagSkyUseRGBEEncoding": "true"
}
```

### Black Wall ❗
> [!CAUTION]
> **Very Buggy**
```json
{
    "FIntCameraFarZPlane": "60"
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
> [!WARNING]
> **Only applies to games with the default skybox**
```json
{
    "FFlagDebugSkyGray": "true",
    "FFlagSkyUseRGBEEncoding": "true"
}
```

### Colorful Sky ❗
> [!CAUTION]
> **Very Buggy**
```json
{
    "DFFlagTextureQualityOverrideEnabled": "true",
    "DFIntTextureQualityOverride": "0",
    "FIntDebugFRMOptionalMSAALevelOverride": "0",
    "FIntVertexSmoothingGroupTolerance": "0",
    "FIntDebugTextureManagerSkipMips": "8",
    "FIntDebugForceMSAASamples": "0"
}
```

### Black Sky
```json
{
    "FIntDebugTextureManagerSkipMips": "8",
    "DFIntTextureQualityOverride": "0",
    "FIntVertexSmoothingGroupTolerance": "10000",
    "DFFlagTextureQualityOverrideEnabled": "true"
}
```

### Pause Voxelizer/Disable Baked Shadows ❗
> [!WARNING]
> **If u play hornor game i dont recommend u use it**
```json
{
    "DFFlagDebugPauseVoxelizer": "true"
}
```

### Mesh Scale Voxelizer
```json
{
    "DFFlagUseMeshScaleInVoxelizer2": "true"
}
```

### Disable Voxelizer Terrain
```json
{
    "DFFlagDebugVoxelizerDisableSIMD": "true",
    "DFFlagVoxelizerDisableTerrainSIMD": "true"
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
> **Combine with [Lighting Attenuation] for better vision**
```json
{
    "FFlagFastGPULightCulling3": "true"
}
```

### Lighting Attenuation ❗
> [!CAUTION]
> **Weird Lighting**
```json
{
    "FFlagNewLightAttenuation": "true"
}
```

### Custom Frame Buffer 🌟
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
> **0 -> 4 for less quality 16, 32, 64 for higher quality**
```json
{
    "FIntTerrainArraySliceSize": "0"
}
```

### High Quality Textures 
> [!NOTE]
> **0 -> 3**
```json
{
    "DFFlagTextureQualityOverrideEnabled": "true",
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

### Force MSAA 🌟
> [!NOTE]
> **1 -> 7**
```json
{
    "FIntDebugForceMSAASamples": "1",
    "FIntDebugFRMOptionalMSAALevelOverride": "1"
}
```

### ShadowMap Bias 
> [!NOTE]
> **[Future & ShadowMap]**
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
> **Very Buggy**
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
    "FFlagHighlightOutlinesOnMobile": "true",
    "DFFlagVisBugHighlightImprovement": "true"
}
```

### Enable Gpu Texture Compressor 🌟
``` json
{
    "FFlagRenderGpuTextureCompressor": "true"
}
```

### Enable HSR
``` json
{
    "FFlagDebugForceGenerateHSR": "true",
    "FFlagHSRClusterImprovement": "true",
    "FFlagHSRRemoveDuplicateindices": "true"
}
```

### Simulation Optimization Flag 🌟
> [!NOTE]
> **Optimization, latency, delay FFlag**
``` json
{
    "FFlagSimDcdEnableLAR3": "true",
    "FFlagSimDcdRefactorDelta3": "true",
    "DFIntBufferCompressionLevel": "0",
    "DFIntBufferCompressionThreshold": "100",
    "DFIntPerformanceControlFrameTimeMax": "1",
    "DFIntPerformanceControlFrameTimeMaxUtility": "-1",
    "DFIntAnimatorThrottleMaxFramesToSkip": "0",
    "DFIntNumFramesAllowedToBeAboveError": "0",
    "DFIntVisibilityCheckRayCastLimitPerFrame": "10",
    "DFIntNetworkSchemaCompressionRatio": "50",
    "DFIntTimeBetweenSendConnectionAttemptsMS": "100"
}
```

### Vertex Smoothing Group Tolerance
> [!WARNING]
> **The FIntVertexSmoothingGroupTolerance flag controls the tolerance level for vertex smoothing groups in 3D graphics.**
> 
> **Lower values result in lower smoothing quality as more errors are tolerated, making models appear more angular and less smooth.**
> 
> **Higher values increase the smoothing accuracy, leading to smoother, more visually appealing models with fewer artifacts.**
``` json
{
    "FIntVertexSmoothingGroupTolerance": "1000"
}
```

### Directional Attenuation Max Points
> [!WARNING]
> **Lower values: May improve performance but reduce lighting accuracy. > Higher values: Increase lighting accuracy at the cost of performance, potentially leading to slower rendering, especially in scenes with complex lighting setups.**
> 
> **Explanation: Limits the maximum number of sample points for calculating directional light attenuation.**
> 
> **Lower values improve performance but may reduce lighting accuracy.**
> 
> **Higher values increase lighting accuracy but may slow rendering in complex lighting setups.**
``` json
{
    "FIntDirectionalAttenuationMaxPoints": "400"
}
```

### Better shadows ❗
> [!WARNING]
> **Loading will take longer but the shadows are much better**
``` json
{
    "FFlagRenderInitShadowmaps": "true"
}
```

### Raycast Performance Improvements 🌟
> [!NOTE]
> **https://create.roblox.com/docs/workspace/raycasting**
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

### New Version of Render 🌟
> [!NOTE]
> **Enables an updated rendering system to improve performance and manage render calls.**
``` json
{
    "FFlagRenderCBRefactor2": "true"
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

### Makes Avatars Shiny 
```json
{
    "DFIntRenderClampRoughnessMax": "-640000000",
    "DFIntDebugFRMQualityLevelOverride": "6"
}
```

### Limits number of animations being played ❗
```json
{
    "DFIntMaxActiveAnimationTracks": "0"
}
```

### Remove Bloom 🌟
``` json
{
    "FIntBloomFrmCutoff": "1654515"
}
```



<h1 align="center">Telemetry</h1>



### Dont Ur Report Stuff To A Random Website
> [!NOTE]
> **rss means it sends stuff to different website**
```json
{
    "DFFlagAndroidReportPeakRSS": "false"
}
```

### Disable Mobile Advertising
> [!NOTE]
> **Android Only**
```json
{
    "FFlagSendMobileAdvertisingIdEnabled2": "false",
    "FFlagSendMobileAdvertisingIdEnabledAndroid2": "false"
}
```

### Remove Minimum required Memory For Roblox
```json
{
    "FIntMininumRequiredMemoryInGB": "0",
    "FIntMininumRequiredMemoryInMB": "0"
}
```

### Zero Telemetry
```json
{
    "DFStringTelemetryV2Url": "null",
    "DFStringHttpPointsReporterUrl": "null",
    "FFlagEnableServiceInitBreakdownTelemetry": "false",
    "DFFlagReportReplicatorStatsToTelemetryV22": "false",
    "DFFlagDebugDisableTelemetryAfterTest": "true",
    "FFlagEnableTelemetryProtocol": "false",
    "FFlagEnableTelemetryService1": "false",
    "FFlagOpenTelemetryEnabled2": "false",
    "FLogRobloxTelemetry": "0",
    "FFlagTimeAndNewJoinDataTelemetry": "false",
    "FFlagDisableMemoryTracking": "true",
    "DFStringRobloxAnalyticsURL": "null",
    "FFlagLuaAppDesktopMediaGalleryTelemetry": "false",
    "FFlagMediaAccordionAndFullTelemetry": "false",
    "DFStringRobloxTelemetryReliabilityCountAllowList": "null"
}
```

### Disable Telemetry VNG (Vietnamese User)
```json
{
    "FFlagEnableVNGNewAppAvailableModal": "false",
    "FFlagVngLogoutGlobalAppSessionsOnConversion": "false",
    "FFlagLuaAppHomeVngAppUpsell": "false",
    "FFlagVngTOSRevisedEnabled": "false",
    "FStringVNGWebshopUrl": "null"
}
```

### Disable Telemetry China
```json
{
    "FStringTencentAuthPath": "null",
    "FLogTencentAuthPath": "null",
    "FStringDevPublishChinaRequirementsLink": "null",
    "FLogDevPublishChinaRequirementsLink": "null"
}
```

### Don't Give Roblox Info On Your Device
```json
{
    "DFIntReportDeviceInfoRate": 0,
    "DFIntReportOutputDeviceInfoEventRateHundredthsPercentage": 0,
    "DFIntReportOutputDeviceInfoRateHundredthsPercentage": 0,
    "DFIntReportRecordingDeviceInfoEventRateHundredthsPercentage": 0,
    "DFIntReportRecordingDeviceInfoRateHundredthsPercentage": 0
}
```

### Disable In-game Advertisements 🌟
```json
{
    "FFlagAdServiceEnabled": "false",
    "FLogAdService": 0
}
```

### Disable events tab/change its url
```json
{
    "FFlagPlatformEventEnabled2": "false",
    "FStringPlatformEventUrl": "https://www.google.com/"
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
> [!NOTE]
> **Setting this to True will not do anything**
> 
> **[TIP] Use PlaceFilter for specific games**
```json
{
    "DFFlagVoiceChat4": "false"
}
```

### Log chat yourself
```json
{
    "FFlagDebugShowTextBounds": "true"
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



<h1 align="center">Quality of Life</h1>



### Smoother/Faster Input 🌟
> [!NOTE]
> **When enabled the game will use an updated implementation for processing user input, which may lead to smoother and more responsive interactions. This flag controls the refactoring of the legacy input handling system in Roblox.**
``` json
{
    "FFlagLuaAppLegacyInputSettingRefactor": "true"
}
```

### Stuttery Animation Fix 🌟
```json
{
    "DFIntTimestepArbiterThresholdCFLThou": "300"
}
```

### Adjust Default Timeout Time
> [!NOTE]
> **1 second = 1000**
```json
{
    "DFIntDefaultTimeoutTimeMs": "5000"
}
```

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
    "FFlagUserShowGuiHideToggles2": "true"
}
```

### Hide Guis
| Key combination   | Action                                                                    |
| ----------------- | ------------------------------------------------------------------------- |
| Ctrl + Shift + B  | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc)                |
| Ctrl + Shift + C  | Toggles game-defined ScreenGuis                                           |
| Ctrl + Shift + G  | Toggles Roblox CoreGuis                                                   |
| Ctrl + Shift + N  | Toggles player names, and other BillboardGuis that show up above a player |
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

### Spammed letters ❗
> [!WARNING]
> **This fflag basically spams every other letter on roblox coregui and the game's gui but it doesn't affect some parts of the games!**
> 
> **Default is 0 and if you set it to anything higher it just follows whatever number you put**
```json
{
    "FIntDebugTextElongationFactor": "999999"
}
```

### MTU ❗
> [!WARNING]
> **700 -> 1500**
>
> **Risks caused by yourself**
```json
{
    "DFIntConnectionMTUSize": "MTU_HERE"
}
```

### No Internet Disconnect ❗
> [!CAUTION]
> **You will still be kicked but the message wont show.**
```json
{
    "DFFlagDebugDisableTimeoutDisconnect": "true"
}
```

### Disable New Chat Report
``` json
{
    "DFFlagChatLineAbuseReportAPIEnabled2": "false"
}
```

### Lets you change the zoom out limit
> [!NOTE]
> **Only applies to games that has not changed the default zoom limit**
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
> [!NOTE]
> **Pretty self explanatory fflag, you can't disable them using the hotkey**
```json
{
    "FFlagDebugAlwaysDisplayRenderStats": "true"
}
```

### Subscriptions Page
```json
{
    "FFlagLuaAppDevSubsEnabled": "true",
    "DFFlagDeveloperSubscriptionsEnabled": "true"
}
```

### Adjust Scroll Speed
```json
{
    "FIntScrollWheelDeltaAmount": "140"
}
```

### Custom MicroProfiler Scale
```json
{
    "DFIntMicroProfilerDpiScaleOverride":  "100"
}
```

### Capture posts
> [!NOTE]
> **Twitter x Roblox Edition**
```json
{
    "FFlagCapturesPostEnabledForAll_v4": "true"
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

### Disable Feedback Button in ESC
```json
{
    "FFlagDisableFeedbackSoothsayerCheck": "false"
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
    "FFlagTopBarUseNewBadge": "false",
    "FFlagControlBetaBadgeWithGuac": "false"
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
> [!WARNING]
> **Only works on web view windows like profiles, ctrl + shift + I**
```json
{
    "FFlagDebugEnableNewWebView2DevTool": "true"
}
```

### Show All Error Strings ❗
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

### Preferred Text Size Scale 🌟
``` json
{
     "FFlagEnablePreferredTextSizeGuiService": "true",
     "FFlagEnablePreferredTextSizeScale": "true",
     "FFlagEnablePreferredTextSizeSettingInMenus2": "true"
}
```

### Disable Toast Notifications 🌟
```json
{
    "FFlagToastNotificationsProtocolEnabled2": "false"
}
```

### Cleaner desktop home page 🌟
```json
{
    "FIntGameGridFlexFeedItemTileNumPerFeed": "0"
}
```

### Disable Take A Screenshot of This 🌟
```json
{
    "FFlagTakeAScreenshotOfThis": "false"
}
```

### Do not trace ping
```json
{
    "DFFlagDataPingTrace": "false",
    "DFFlagRakNetPingTrace": "false"
}
```

### Max delay for layout updates
> [!NOTE]
> **basically the things that are changing on an ui for example loading a new page**
```json
{
    "DFIntMaxAcceptableUpdateDelay": "60"
}
```



<h1 align="center">User Interface/Visuals Experimental</h1>



### Turn on VC in Party (requires VC obviously)
```json
{
    "FFlagEnablePartyVoiceOnlyForUnfilteredThreads": "false",
    "FFlagEnablePartyVoiceOnlyForEligibleUsers": "false"
}
```

### Draggable Capture Button
```json
{
    "FFlagEnableUpdatedCaptureControls_v8": "true"
}
```

### Network Menu Update Rate
> [!NOTE]
> **This fast flag configures how often the network stats menu (Shift + F3) updates its information. By default, it refreshes the information every 1 second.**
>
> **If the value is set to max negative (-2147483647), the information is updated very quickly.**
```json
{
    "FIntNetworkStatRefreshRate": "1"
}
```

### Rename Connections Back To Friends 🌟
```json
{
    "FFlagRenameFriendsToConnections": "false",
    "FFlagRenameFriendsToConnectionsAppChat2": "false",
    "FFlagRenameFriendsToConnectionsCoreUI": "false",
    "FFlagRenameFriendsToConnectionsFriendsMenu": "false",
    "FFlagRenameFriendsToConnectionsFriendsPage": "false",
    "FFlagRenameFriendsToConnectionsPartyLobby": "false",
    "FFlagRenameFriendsToConnectionsProfile": "false"
}
```

### Disable centered experience details page 🌟
```json
{
    "FFlagLuaAppEdpSingleColumn": "false",
    "FFlagLuaAppEdpSingleColumnIxp": "false",
    "FFlagLuaAppEdpSingleColumnAcrossPlatformsIxp": "false"
}
```

### Dont Delay Surface App 🌟
```json
{
    "FFlagPerformanceControlDelaySingleSurfaceAppInit": "false"
}
```

### No more homepage/infinite scrolling 🌟
> [!NOTE]
> **Default = 30**
```json
{
    "FIntTooltipHitboxMinSize": "2147483647"
}
```

### No opacity to Chrome UI
```json
{
    "FFlagChromeUsePreferredTransparency": "false"
}
```

### Multi Try On
> [!NOTE]
> **Allows you to try on multiple things in the catalog and buy everything at once**
```json
{
   "FFlagAXEnableMultiTryOnUI": "true"
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

### Red font
> [!NOTE]
> **You need to use Default Roblox Font to activate this. Also it can be glitchy in the settings menu.**
```json
{
    "FStringDebugHighlightSpecificFont": "rbxasset://fonts/families/BuilderSans.json"
}
```

### ps-ps (Pseudolocalisation)
```json
{
    "FFlagDebugEnablePseudolocalization": "true",
    "FFlagDebugEnableCoreScriptPseudolocalization": "true"
}
```

### Change How Much Letters In Text
> [!NOTE]
> **This fastflag basically spams every other letter on ROBLOX CoreGUI and the game's GUI but it doesn't affect some parts of the games.**
>
> **Default Value: [7]**
```json
{
    "FIntDebugTextElongationFactor": "999999"
}
```



<h1 align="center">Audio & Sound</h1>



### Uncap Sound Limit
```json
{
    "DFIntDebugAudioMaxDecibels": "2147483647"
}
```

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
> [!NOTE]
> **Default: [Min 7 Max 80]**
```json
{
    "DFIntVoiceChatRollOffMinDistance": "7",
    "DFIntVoiceChatRollOffMaxDistance": "80"
}
```

### Sounds use physical velocity and become distorted
> [!NOTE]
> **<2017 but still work**
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
> [!NOTE]
> **Default = 1000**
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



<h1 align="center">Latency & Other</h1>



### Get Back Oof 🌟
```json
{
    "FFlagBringBackOof": "true"
}
```

### Disable Show Install Success Prompt
```json
{
    "ShowInstallSuccessPrompt": "false"
}
```

### Optimize VR Matrices
```json
{
    "DFFlagOptimizeVRMatrices": "true",
    "DFFlagVisBugFixVR": "true"
}
```

### Real Time Animation Refactor ❗
> [!WARNING]
> **Increase CPU load.**
```json
{
    "FFlagRealTimeAnimationEnableRefactor": "true"
}
```

### Network Ownership
> [!NOTE]
> **https://create.roblox.com/docs/physics/network-ownership**
``` json
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000",
    "DFFlagDebugPhysicsSenderDoesNotShrinkSimRadius": "true",
    "FFlagDebugUseCustomSimRadius": "true"
}
```

### Better Latency and Loading Speed 🌟
> [!WARNING]
> **Can make your Roblox use 4-6gb of memory**
```json
{
    "DFIntMemoryUtilityCurveBaseHundrethsPercent": "10000",
    "DFIntMemoryUtilityCurveNumSegments": "100",
    "DFIntMemoryUtilityCurveTotalMemoryReserve": "0"
}
```

### Disable Walk Speed Scale Based
``` json
{
    "DFFlagUserAnimateScaleRun": "false"
}
```

### Lower Micro Lags With Camera Movement 🌟
> [!NOTE]
> **Tracks the last input type (Keyboard, Mouse, Gamepad, VR Controller).**
```json
{
    "FFlagUserCameraControlLastInputTypeUpdate": "false"
}
```

### Enable SmoothInputOffset 🌟
> [!NOTE]
> **"Smooth Input Offset" helps deliberately slow down or filter input signals, making mouse or controller movements smoother and preventing sudden stuttering or jittering.**
```json
{
    "FFlagSmoothInputOffset": "true"
}
```

### Faster Precise Time 🌟
> [!NOTE]
> **Faster response: Helps actions like jumping, shooting, or moving become more precise and instantaneous.**
>
> **Smoother visual effects: Effects like lighting and physics-based movements are updated more accurately in real time.**
```json
{
    "FFlagFasterPreciseTime4": "true"
}
```

### Enable CoalesceInput (Smooth Multi Responsive)🌟
> [!NOTE]
> **Feature or input processing technique that combines multiple control signals into a smoother and faster-responding. It is commonly used to improve sensitivity and accuracy when players interact with the game using a keyboard, mouse, controller, or touch input.**
```json
{
    "FFlagCoalesceInput": "true"
}
```

### Keyboard,Mouse,Gamepad,Touch Latency 🌟
> [!NOTE]
> **Default value: 500 >> Lower value = more responsive.**
``` json
{
    "FIntActivatedCountTimerMSKeyboard": "0",
    "FIntActivatedCountTimerMSMouse": "0",
    "FIntActivatedCountTimerMSGamepad": "0",
    "FIntActivatedCountTimerMSTouch": "0"
}
```

### Zero Delay with Mouse 🌟
> [!NOTE]
> **Default value: 16 >> Lower value = more double click.**
``` json
{
    "FIntCLI20390_2": "0"
}
```

### Roblox Input Runtime
```json
{
    "FFlagRobloxInputUsesRuntime2": "true"
}
```

### Better serversided character position
> [!NOTE]
> **100 makes your serversided character closer to your client**
```json
{
    "DFIntS2PhysicsSenderRate": "100"
}
```

### Stop Shrinking Simulation Radius 🌟
> [!NOTE]
> **Normally, DFIntS2PhysicsSenderRate controls how much physical data is being sent and increases synchronization with the server, but the simulation radius (the area around you where physics are actively processed) gets reduced over time.**
```json
{
    "DFFlagDebugPhysicsSenderDoesNotShrinkSimRadius": "true"
}
```

### Dev Console Logging 🌟
> [!NOTE]
> **Changes how long a Message can be, doesn't give you the ability to exceed the 16k Message Length Limit.**
```Json
{
    "FIntStandardOutputMaximumCharacterLength": "1"
}
```

### Dev Console Log Count 🌟
> [!NOTE]
> **Control how many developer console logs can be shown at once, for example if you set the limit to be 100, then 100 different log messages will be shown while any older ones will be deleted when the limit is reached.**
``` json
{
    "FIntNewDevConsoleMaxLogCount": "2"
}
```

### Replace all Decals with a Test Image
```json
{
    "FFlagDebugTestImageDrawItem": "true"
}
```

### Allows you to edit the DataModel Patch ❗
> [!WARNING]
> **Low chance get banned by roblox**
>
> **risk by yourself**
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


<h1 align="center">[BloxsTrap Any Version]</h1>



<h1 align="center">Windows</h1>



## [Bloxstrap Official>>>>>](https://github.com/bloxstraplabs/bloxstrap/releases/)
## [Fishstrap>>>>>](https://github.com/fishstrap/fishstrap/releases/)
## [Lunastrap>>>>>](https://github.com/lunastraplabs/lunastrap/releases/)
## [Froststrap>>>>>](https://github.com/Meddsam/Froststrap/releases/)
## [Voidstrap (Discontinued)>>>>>](https://github.com/voidstrap/Voidstrap/releases/)
## [Plexity (Release)>>>>>](https://github.com/KloBraticc/Plexity/releases/)



<h1 align="center">MacOS</h1>



## [Appleblox>>>>>](https://github.com/AppleBlox/appleblox/tags)



<h1 align="center">Linux</h1>



## [Rober>>>>>](https://sober.vinegarhq.org/)



<h1 align="center">Android</h1>



## [Chevstrap>>>>>](https://github.com/FrosSky/Chevstrap/releases)
