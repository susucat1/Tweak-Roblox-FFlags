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

### Unified lighting (LightGrid - Beta)
```json
{
    "FFlagRenderUnifiedLighting": "true"
}
```
