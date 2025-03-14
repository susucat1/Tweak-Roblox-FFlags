<h1 align="center">Tweak Roblox FFlags</h1>


![image](https://github.com/bloxstraplabs/bloxstrap/raw/main/Images/Bloxstrap-full-dark.png#gh-dark-mode-only)
# [Bloxstrap Download >>>>>](https://github.com/bloxstraplabs/bloxstrap/releases/)

![image](https://github.com/returnrqt/bloxstrap/raw/main/Images/Bloxstrap-full-dark.png#gh-dark-mode-only)
# [Fishtrap Download >>>>>](https://github.com/returnrqt/fishstrap/releases/)

## How to Fix 403 in <2.5.4 Bloxstrap
![image](http://web.archive.org/web/20240705210210im_/https://private-user-images.githubusercontent.com/166893422/340889199-e1f50b6f-8d62-434c-a95b-4ff535127c09.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAyMTM2MzAsIm5iZiI6MTcyMDIxMzMzMCwicGF0aCI6Ii8xNjY4OTM0MjIvMzQwODg5MTk5LWUxZjUwYjZmLThkNjItNDM0Yy1hOTViLTRmZjUzNTEyN2MwOS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcwNVQyMTAyMTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zYTEzNGY1OThiNjIzMmRmNjFjMTE2MmNkOTY3ZTEzNzNlOGQzNWM4NzZjZDEwMjY3NWVmNzE3NDE4M2QzYjcxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.kBc2QqZGcGxbp_bn2gRBxD1vbrPZ04nZGJfzGW_FVsc)
#### 1. `%localappdata%\Bloxstrap\Settings.json` or `%appdata%\Bloxstrap\Settings.json`
#### 2. Inside the contents of the file you will find `"Channel": "example"`
#### 3. Now change that to `"Channel": "LIVE"`
#### 4. Your configuration is complete!
## Why does this happen?: Because the channel you are assigned to is a common channel.

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

### Direct X 10
> [!NOTE]
> **FOR POTATO DESKTOP**
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
> **Note!: Visual Crashes**
```json
{
    "FFlagDebugGraphicsDisableDirect3D11": "true",
    "FFlagDebugGraphicsPreferVulkan": "true"
}
```

### Metal
> [!WARNING]
> **Note!: MacOS Only**
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
    "FFlagRenderUnifiedLighting12": "true"
}
```
<h1 align="center">Graphical Settings</h1>

### Disable Dynamic Resolution Scale
```json
{
    "FFlagRenderDynamicResolutionScale12": "false"
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
> **Value: 1 -> Unlimited**
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
##### You can change number and work with Unified Lighting
```json
{
    "FIntRenderMaxShadowAtlasUsageBeforeDownscale": "-1"
}
```
### Disable Highlights on Parts
```json
{
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
> [!NOTE]
> **You can use it or roblox default**
```json
{
    "FIntTaskSchedulerThreadMin": "0",
    "FIntRuntimeMaxNumOfThreads": "2400"
}
```
### HyperThreading
> [!NOTE]
> **Default by roblox**
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

### Force Graphics Quality Level 
##### Note: 1-21
```json
{
    "FIntRomarkStartWithGraphicQualityLevel": "1"
}
```

### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels 🌟
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```json
{
    "DFIntDebugFRMQualityLevelOverride": "1"
}
```

### Low Render Distance
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
    "FIntRenderLocalLightUpdatesMax": "10"
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
### Gray Sky
> [!NOTE]
> **You can use it or Roblox Default**
```json
{
    "FFlagDebugSkyGray": "true"
}
```
### Pause Voxelizer/Disable Baked Shadows
> [!WARNING]
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
> [!CAUTION]
> **Weird Lighting**
```json
{
    "FFlagNewLightAttenuation": "true"
}
```
### Frame Buffer 🌟
> [!NOTE]
> **0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag**
```json
{
    "DFIntMaxFrameBufferSize": "4"
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
###### 1-3
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
###### 1-7
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
### Faster preloading 🌟
``` json
{
    "DFIntAssetPreloading": "9999999",
    "DFIntNumAssetsMaxToPreload": "9999999"
}
```
### Reduce avatar item particles in first person
> [!NOTE]
> **Default by Roblox**
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
> [!NOTE]
> **Note!: Server Sided**
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
> [!CAUTION]
> **BUG cant loading fully item avatar**
``` json
{
    "FFlagEnableQuickGameLaunch": "true"
}
```
### Enable Highlight Outlines on any Rendering API
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
### Enable HSR (Hidden Surface Removal)
> [!NOTE]
> **its working like occlusion culling**
``` json
{
    "FFlagDebugForceGenerateHSR": "true"
}
```
### Enable Old Lighting Compatibility
``` json
{
    "FFlagRemoveLightingCompatibilityCode2": "false"
}
```
### Simulation Optimization Flag
##### Optimization, latency, delay FFlag
``` json
{
    "DFIntBufferCompressionLevel": "0",
    "DFIntBufferCompressionThreshold": "100",
    "DFIntPerformanceControlFrameTimeMax": "1",
    "DFIntPerformanceControlFrameTimeMaxUtility": "-1",
    "FFlagPushFrameTimeToHarmony": "true",
    "DFIntAnimatorThrottleMaxFramesToSkip": "0",
    "DFIntNumFramesAllowedToBeAboveError": "0",
    "DFIntVisibilityCheckRayCastLimitPerFrame": "10",
    "DFIntNetworkSchemaCompressionRatio": "50",
    "DFIntTimeBetweenSendConnectionAttemptsMS": "50",
    "FIntInterpolationAwareTargetTimeLerpHundredth": "100",
    "DFIntMaxAverageFrameDelayExceedFactor": "0"
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
### Raycast Performance Improvements
##### [Review](https://create.roblox.com/docs/workspace/raycasting)
> [!NOTE]
> **if u dont know just ignore it**
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
    "FFlagEnableVisBugChecks28": "true"
}
```
### Move Pre-Render Phase [~25% Performance Boost] 🌟
```json
{
    "FFlagMovePrerenderV2": "true"
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
### Simulation Optimization Flag
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
    "FStringTencentAuthPath": "null"
}
```
### Disable In-game Advertisements 🌟
```json
{
    "FFlagAdServiceEnabled": "false"
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

<h1 align="center">Quality of Life</h1>

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
### Better Trackpad Scrolling
##### For Laptop User use trackpad
``` json
{
    "FFlagBetterTrackpadScrolling": "true"
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

<h1 align="center">User Interface/Visuals</h1>

### Fix Reduced Motion Stuck
###### @kezcn
![image](https://github.com/user-attachments/assets/cfdc9732-084e-4c09-bc43-8039a3bf0d89)
```json
{
    "FFlagFixReducedMotionStuckIGM2": "true"
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
### Disable New Camera Mode
``` json
{
    "FFlagNewCameraControls": "false"
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
### Preferred Text Size Settings (Fully)
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

<h1 align="center">User Interface/Visuals Experimental</h1>

### Chrome UI TopBar
```json
{
    "FFlagEnableReportAbuseMenuRoactABTest2": "true",
    "FFlagEnableInGameMenuChromeABTest2": "true",
    "FFlagEnableInGameMenuChromeABTest3": "true"
}
```
### Chrome UI Topbar Removal
```json
{
    "FFlagEnableInGameMenuChromeABTest2": "false",
    "FFlagEnableReportAbuseMenuRoactABTest2": "false",
    "FFlagEnableInGameMenuChromeABTest3": "false"
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

<h1 align="center">Latency & Another</h1>

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
