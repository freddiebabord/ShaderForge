ShaderForge was originally developed by Freya Holmér (Formerly known as Joachim Holmér) and was made open source in May 2018.
This repo contains fixes to make ShaderForge work with Unity 2018 as well as adding support for additional features listed below.

Thank you to Freya Holmér for making ShaderForge open source and giving what has been an influential tool for us Unity Devs to make some amazing shaders over the years!

While this version of ShaderForge *should* work in Unity versions below 2018, I am not testing any compatability with it at this stage. This version has been tested on Unity 2018.1.0f2.

## Changelog
### 13th May 2018
#### New Features:
+ Unity 2018 support (No SRP support yet. 3D and 2D templates should work)
+ Vulkan shader compile support
+ Metal preview by default on MacOS
+ Changes include render platforms to exclude render patforms
  + Will now compile for all platforms by default
+ Lighting fix from LIGHT_ATTENUATION(i) to unity_4LightAtten0
+ Displays the correct render target under the preview window
+ Beta versioning number
+ HDR Color
  + Enabled HDR color picker
  + Color nodes are HDR by default
  
#### Breaking Changes:
- Removed Substance Material Support
  + Potentially to be readded at a leater date with new Substance package on the assets store
  
#### Git Changes:
+ Moved licence from README to LICENCE
