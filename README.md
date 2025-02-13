<h1 align="center">Tweak-Roblox-FFlags</h1>
<h1 align="center">[Bloxstrap](https://github.com/bloxstraplabs/bloxstrap/releases/)</h1>

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
    "FFlagRenderUnifiedLighting12": "true"
}
```
<h1 align="center">Graphical Settings</h1>

### Dynamic Resolution Scale 🌟
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
### Improve FPS and Smooth out your game 🌟
```json
{
    "DFIntTimestepArbiterDebounceFrames": "2147483647"
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

### Disable Shadows 🌟
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

### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels 🌟
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

### Force LOD on Meshes 🌟
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
### Frame Buffer 🌟
> **Note!: Explnation: 0 makes white screen 1-3 makes other players have laggy movement, 4 is stable has better performance than 10 and less input lag**
```json
{
    "DFIntMaxFrameBufferSize": "4"
}
```
### Target Time & Frame Delay Performance 🌟
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
### Faster preloading 🌟
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
### Move Pre-Render Phase [~25% Performance Boost] ❗
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
### New Version of Render 🌟
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
### Disable Autocomplete
``` json
{
    "FFlagEnableCommandAutocomplete": "false"
}
```
### Disable Avatar Chat
```json
{
    "FFlagAvatarChatServiceEnabled3": "false"
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
### Disable New Dark Theme + Blue Button
```json
{
   "FFlagUIBloxUseNewThemeColorPalettes": "false",
   "FFlagLuaAppEnableFoundationColors7": "false",
   "FFlagLuaAppUseUIBloxColorPalettes1": "false"
}
```
### Party Voice early access
```json
{
    "FFlagEnablePartyVoiceOnlyForUnfilteredThreads": "false",
    "FFlagEnablePartyVoiceOnlyForEligibleUsers": "false"
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
### Cleaner home page
```json
{
    "FIntGameGridFlexFeedItemTileNumPerFeed": "0"
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
### Preferred text size scale
##### enables a font scaler in the escape menu
##### found by Sky (364112742153584640) in Bloxstrap stuff
``` json
{
     "FFlagEnablePreferredTextSizeScale": "true",
     "FFlagEnablePreferredTextSizeSettingInMenus2": "true"
}
```
### Preferred Text Size Settings (new)
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
### Disable Haptics Option
``` json
{
    "FFlagAddHapticsToggle": "false"
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
### No Transparency V4 Menu **(2023)**
```json
{
    "FStringInGameMenuModernizationStickyBarForcedUserIds": "UserID"
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

### Menu V2
```json
{
    "FIntNewInGameMenuPercentRollout3": "100",
    "FFlagEnableInGameMenuControls": "false",
    "FFlagDisableNewIGMinDUA": "true",
    "FFlagEnableInGameMenuChromeABTest4": "false"
}
```
### Menu V4 ❗
```json
{
    "FFlagEnableInGameMenuControls": "false",
    "FFlagDisableNewIGMinDUA": "true",
    "FFlagEnableInGameMenuChromeABTest4": "false"
}
```
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
###### better [network ownership](https://create.roblox.com/docs/physics/network-ownership) of parts
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
  "FIntActivatedCountTimerMSKeyboard": "5"
}
```
### Mouse Latency 🌟
##### Default value: 500 > > Lower value = more responsive mouse
##### This flag determines the mouse input delay in milliseconds. A lower value (such as 1) will reduce the latency between mouse movement or clicks and the game's response, making the mouse feel more responsive. However, setting the value too low could result in excessively sensitive mouse input, potentially leading to issues like unintended multiple clicks or overly sensitive pointer movements. The default value of 500 milliseconds provides a balance between responsiveness and control, reducing the risk of input errors.
``` json
{
  "FIntActivatedCountTimerMSMouse": "5"
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
