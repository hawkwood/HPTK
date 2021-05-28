# HPTK [![](https://img.shields.io/badge/unity-2019.4%20or%20later-green.svg)](https://unity3d.com/es/get-unity/download/archive) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/jorgejgnz/HPTK/blob/master/LICENSE.md) [![version](https://img.shields.io/badge/version-0.6.0-blue)](https://github.com/jorgejgnz/HPTK/releases) [![](https://img.shields.io/discord/679793598958403620?logo=discord)](https://discord.gg/TuzhMZQpDy) [![](https://img.shields.io/twitter/follow/jorgejgnz.svg?label=Follow&style=social)](https://twitter.com/intent/follow?screen_name=jorgejgnz)

**Hand Physics Toolkit (HPTK)** is a toolkit to implement hand-driven interactions in a modular and scalable way. Platform-independent. Input-independent. Scale-independent. Can be combined with [MRTK-Quest](https://github.com/provencher/MRTK-Quest) for UI interactions.

- You can clone a ready-to-go project at [HPTK-Sample](https://github.com/jorgejgnz/HPTK-Sample).

![Screenshot](https://imgur.com/iH35YoZ.jpg)

## Main features
- **Data model** to access parts, components or calculated values with very little code
- **Code architecture** based on MVC-like modules. Support to custom modules
- **Platform-independent.** Tested on VR/AR/non-XR applications
- **Input-independent.** Use hand tracking or controllers
- **Pupettering** for any avatar or body structure
- **Scale-independent.** Valid for any hand size
- **Realistic** configurable **hand physics**
- Define strategies to deal with tracking loss
- Physics-based hover/touch/grab detection
- Tracking noise smoothing

# Supported versions
- Unity 2020.x
- Unity 2019.x

# Supported input
## Hand tracking
- Oculus Quest 1/2 - Android
- Hololens 2 - UWP

## Controllers
- Oculus Touch
- WMR
- Vive
- OpenVR

# Supported render pipelines
- Universal Render Pipeline (URP)
- Standard RP

# Getting started with HPTK (Oculus Quest)

1. Obtain **HPTK**
1. Change **ProjectSettings & BuildSettings**
1. Import the built-in **integration packge** (if needed)
1. Drag & drop the **default setup** to your scene
1. **Build and test**

Check Wiki for a detailed **step-by-step guide**.

# Author
**Jorge Juan González** - *HCI Researcher at I3A (University of Castilla-La Mancha)*

[LinkedIn](https://www.linkedin.com/in/jorgejgnz/) - [Twitter](https://twitter.com/jorgejgnz) - [GitHub](https://github.com/jorgejgnz)

## Acknowledgements

**Oxters Wyzgowski** - [GitHub](https://github.com/oxters168) - [Twitter](https://twitter.com/OxGamesCo)

**Michael Stevenson** - [GitHub](https://github.com/mstevenson)

Nasim, K, Kim, YJ. Physics-based assistive grasping for robust object manipulation in virtual reality. Comput Anim Virtual Worlds. 2018; 29:e1820. [https://doi.org/10.1002/cav.1820](https://doi.org/10.1002/cav.1820)

Linn, Allison. Talking with your hands: How Microsoft researchers are moving beyond keyboard and mouse. The AI Blog. Microsoft. 2016
[https://blogs.microsoft.com/](https://blogs.microsoft.com/ai/talking-hands-microsoft-researchers-moving-beyond-keyboard-mouse/)

# License
[MIT](./LICENSE.md)
