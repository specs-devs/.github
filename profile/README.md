<div align="center">

<img src="https://raw.githubusercontent.com/specs-devs/.github/main/profile/Spectacles_NB.png" width="600" height="auto" align="center">

# Spectacles

**The official GitHub for Spectacles**

*Where you can find the best projects to start your AR developer journey. Let's build the future.*

[![Website](https://img.shields.io/badge/-Website-1a1a1a?style=flat&labelColor=1a1a1a&logo=google-chrome&logoColor=white)](https://www.spectacles.com/)
[![Reddit](https://img.shields.io/badge/-Reddit-ff4500?style=flat&labelColor=ff4500&logo=reddit&logoColor=white)](https://www.reddit.com/r/Spectacles/)
[![Twitter](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white)](https://twitter.com/Spectacles)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&labelColor=E4405F&logo=instagram&logoColor=white)](https://instagram.com/spectacles)
[![YouTube](https://img.shields.io/badge/YouTube-ff0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/feed/subscriptions/UC9YFcJXrGv2QaWbXLq6VN3g)

---

</div>

## Getting Started

Before you begin developing for Spectacles, make sure you have the required tools installed:

**Required Software:**
- **[Lens Studio](https://ar.snap.com/spectacles)** - Snap's free AR development platform for creating Spectacles experiences
- **[Spectacles App (Android)](https://play.google.com/store/apps/details?id=com.snap.spectacles.app&hl=en_US)** - Companion app for Android devices
- **[Spectacles App (iOS)](https://apps.apple.com/us/app/spectacles-by-snap-inc/id6502670261)** - Companion app for iOS devices

---

## About

Specs is the official GitHub organization for Spectacles development resources. We provide open-source tools, frameworks, templates, and comprehensive documentation to help developers build amazing AR experiences for Spectacles. 
> **Lens Studio 5.15.4:** Public [samples](https://github.com/specs-devs/samples/releases/tag/5.15.4) and [packages](https://github.com/specs-devs/packages/releases/tag/5.15.4) are tagged `5.15.4`. Several Sync Kit samples use a `Sync Kit …` folder prefix; the minimal Sync Kit sample folder is **`Sync Kit Basic Example`** (listed here as “Spectacles Sync Kit”). A few legacy demos were removed from this list because they are not published on the public mirror.

Whether you're creating your first AR lens or developing complex spatial applications, we offer the resources and community support you need to succeed.

---

## Samples Repository

Ready-to-use project templates and sample applications demonstrating Spectacles capabilities. Clone individual projects using sparse checkout:

<table width="100%">
<colgroup>
<col width="20%" />
<col width="18%" />
<col width="30%" />
<col width="32%" />
</colgroup>
<tbody>
<tr>
<th>Preview</th>
<th>Title</th>
<th>Description</th>
<th>Clone Command</th>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Agent%20Center/README-ref/agent-park-desk.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Agent%20Center">Agent Center</a></td>
<td>Manage AI coding agents in AR. Chat via text or voice, attach images, and view live agent status as 3D robot avatars</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Agent Center"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Agentic%20Playground/README-ref/sample-list-agentic-playground-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Agentic%20Playground">Agentic Playground</a></td>
<td>Advanced AI playground demonstrating agentic behaviors and autonomous interactions</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Agentic Playground"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/AI%20Music%20Gen/README-ref/sample-list-ai-music-gen-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/AI%20Music%20Gen">AI Music Gen</a></td>
<td>Generate AI music using Google's Lyria model with 3D visualizations</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "AI Music Gen"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/AI%20Playground/README-ref/sample-list-ai-playground-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/AI%20Playground">AI Playground</a></td>
<td>Sample project for AI using Spectacles Remote Service Gateway</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "AI Playground"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Air%20Hockey/README-ref/sample-list-air-hockey-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Air%20Hockey">Sync Kit Air Hockey</a></td>
<td>Multiplayer air hockey game experience</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Air Hockey"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/BLE%20Playground/README-ref/sample-list-ble-playground-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/BLE%20Playground">BLE Playground</a></td>
<td>Bluetooth Low Energy experimentation and testing environment</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "BLE Playground"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Crop/README-ref/sample-list-crop-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Crop">Crop</a></td>
<td>Sample project showing how to crop the environment using hand gesture</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Crop"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Custom%20Locations/README-ref/sample-list-custom-locations-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Custom%20Locations">Custom Locations</a></td>
<td>Map real life areas and create AR experiences around those locations</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Custom Locations"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Depth%20Cache/README-ref/sample-list-depth-cache-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Depth%20Cache">Depth Cache</a></td>
<td>Cache depth frames for pixel-to-3D projection with cloud-based vision models</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Depth Cache"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/DJ%20Specs/README-ref/sample-list-dj-specs-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/DJ%20Specs">DJ Specs</a></td>
<td>Music mixing and DJ experience</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "DJ Specs"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Essentials/README-ref/sample-list-essentials-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Essentials">Essentials</a></td>
<td>Collection of foundational concepts for creating lenses in Lens Studio</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Essentials"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Fetch/README-ref/sample-list-fetch-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Fetch">Fetch</a></td>
<td>Sample project using the Spectacles Fetch API</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Fetch"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20High%20Five/README-ref/sample-list-high-five-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20High%20Five">Sync Kit High Five</a></td>
<td>Hand gesture recognition and interaction example</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit High Five"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Laser%20Pointer/README-ref/sample-list-laser-pointer-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Laser%20Pointer">Sync Kit Laser Pointer</a></td>
<td>Laser pointer interaction and visualization</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Laser Pointer"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Navigation%20Kit/README-ref/sample-list-navigation-kit-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Navigation%20Kit">Navigation Kit</a></td>
<td>Example project for indoors or outdoors navigation</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Navigation Kit"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Path%20Pioneer/README-ref/sample-list-path-pioneer-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Path%20Pioneer">Path Pioneer</a></td>
<td>Sample project for path creation and path walking experience</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Path Pioneer"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Shared%20Sync%20Controls/README-ref/sample-list-shared-sync-controls-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Shared%20Sync%20Controls">Sync Kit Shared Sync Controls</a></td>
<td>Multi-user synchronized controls and interactions</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Shared Sync Controls"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/SnapML%20Chess%20Hints/README-ref/sample-list-chess-hint-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/SnapML%20Chess%20Hints">SnapML Chess Hints</a></td>
<td>AI-powered chess move suggestions using computer vision and SnapML</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "SnapML Chess Hints"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/SnapML%20Pool/README-ref/sample-list-pool-ml-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/SnapML%20Pool">SnapML Pool</a></td>
<td>Uses SnapML to detect a pool table with all 16 balls and pocket holes</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "SnapML Pool"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/SnapML%20Starter/README-ref/sample-list-snapml-starter-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/SnapML%20Starter">SnapML Starter</a></td>
<td>Demonstrates how to leverage SnapML on Spectacles for object detection</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "SnapML Starter"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Spatial%20Image/README-ref/sample-list-spatial-image-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Spatial%20Image">Spatial Image</a></td>
<td>Convert your 2D images to 3D spatial experiences</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Spatial Image"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Spatial%20Anchors/README-ref/sample-list-spatial-persistance-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Spatial%20Anchors">Spatial Anchors</a></td>
<td>Template project using Spectacles Spatial Anchor API</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Spatial Anchors"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Spectacles%20Mobile%20Kit/README-ref/sample-list-mobile-kit-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Spectacles%20Mobile%20Kit">Spectacles Mobile Kit</a></td>
<td>SDK for seamless communication between mobile apps and Lenses via BLE</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Spectacles Mobile Kit"</code></td>
</tr>
<tr>
<td align="center" valign="top"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Basic%20Example/README-ref/sample-list-spectacles-sync-kit-rounded-edges.gif" width="200" alt="Spectacles Sync Kit preview"/></td>
<td align="center" valign="top"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Basic%20Example">Spectacles Sync Kit</a><br/><sub>folder: <code>Sync Kit Basic Example</code></sub></td>
<td valign="top">Minimal Connected Lens example for Spectacles Sync Kit (transform sync).</td>
<td valign="top"><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Basic Example"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Think%20Out%20Loud/README-ref/sample-list-think-out-loud-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Think%20Out%20Loud">Sync Kit Think Out Loud</a></td>
<td>Voice interaction and AI conversation</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Think Out Loud"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Throw%20Lab/README-ref/sample-list-throw-lab-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Throw%20Lab">Throw Lab</a></td>
<td>Sample project demonstrating realistic throwing mechanics in AR</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Throw Lab"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Tic%20Tac%20Toe/README-ref/sample-list-tic-tac-toe-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Tic%20Tac%20Toe">Sync Kit Tic Tac Toe</a></td>
<td>Classic tic-tac-toe game in AR</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Tic Tac Toe"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Voice%20Playback/README-ref/sample-list-voice-playback-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Voice%20Playback">Voice Playback</a></td>
<td>Sample project for recording and playing back audio on Spectacles</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Voice Playback"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Snap%20Cloud%20World%20Kindness%20Day/README-ref/sample-list-world-kindness-day-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Snap%20Cloud%20World%20Kindness%20Day">Snap Cloud World Kindness Day</a></td>
<td>Special event lens celebrating World Kindness Day</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Snap Cloud World Kindness Day"</code></td>
</tr>
</tbody>
</table>

---

## Packages Repository

Reusable components, utilities, and packages for AR development. Clone individual packages using sparse checkout:

<table>
<tbody>
<tr>
<th>Preview</th>
<th>Title</th>
<th>Description</th>
<th>Clone Command</th>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/AccessComponents/Assets/AssetImage/AccessComponents.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/AccessComponents">AccessComponents</a></td>
<td>Accessibility components and utilities for inclusive AR experiences</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add AccessComponents</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/CompositeCameraTexture/Assets/AssetImage/CompositeCameraTexture.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/CompositeCameraTexture">CompositeCameraTexture</a></td>
<td>Advanced camera texture composition utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add CompositeCameraTexture</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/CropCameraTexture/Assets/AssetImage/CropCameraTexture.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/CropCameraTexture">CropCameraTexture</a></td>
<td>Camera texture cropping and manipulation tools</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add CropCameraTexture</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/FaceMesh/Assets/AssetImage/FaceMesh.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/FaceMesh">FaceMesh</a></td>
<td>Face mesh tracking and transform matching for facial landmarks</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add FaceMesh</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/FastUI/Assets/AssetImage/FastUI.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/FastUI">FastUI</a></td>
<td>Runtime UI generation for grids, lists, and dynamic layouts on Spectacles</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add FastUI</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/FunctionCallHelper/Assets/AssetImage/FunctionCallHelper.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/FunctionCallHelper">FunctionCallHelper</a></td>
<td>Helper utilities for function calls and remote execution</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add FunctionCallHelper</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/GuidedInstructions/Assets/AssetImage/GuidedInstructions.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/GuidedInstructions">GuidedInstructions</a></td>
<td>Voice-driven, AI-assisted guided AR flows with depth and speech</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add GuidedInstructions</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/HandAttacher/Assets/AssetImage/HandAttacher.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/HandAttacher">HandAttacher</a></td>
<td>Attach objects to hand joints with smooth interpolation and SIK support</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add HandAttacher</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Instantiation/Assets/AssetImage/Instantiation.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Instantiation">Instantiation</a></td>
<td>Object instantiation and lifecycle management utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add Instantiation</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/InteractableHelper/Assets/AssetImage/InteractableHelper.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/InteractableHelper">InteractableHelper</a></td>
<td>Interactive object helpers and interaction systems</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add InteractableHelper</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/LSTween/Assets/AssetImage/LSTween.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/LSTween">LSTween</a></td>
<td>Animation tweening library for Lens Studio</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add LSTween</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Leaderboard/Assets/AssetImage/Leaderboard.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Leaderboard">Leaderboard</a></td>
<td>Leaderboard and scoring system components</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add Leaderboard</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/MarkerTrackingHelper/Assets/AssetImage/MarkerTrackerHelper.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/MarkerTrackingHelper">MarkerTrackingHelper</a></td>
<td>Marker tracking and recognition utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add MarkerTrackingHelper</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/MocopiReceiver/Assets/AssetImage/MocopiReceiver.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/MocopiReceiver">MocopiReceiver</a></td>
<td>Stream Sony mocopi motion data for full-body avatar animation</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add MocopiReceiver</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/RemoteServiceGateway/Assets/AssetImage/RemoteServiceGateway.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/RemoteServiceGateway">RemoteServiceGateway</a></td>
<td>Remote service integration and API gateway</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add RemoteServiceGateway</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/RuntimeGizmos/Assets/AssetImage/RuntimeGizmos.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/RuntimeGizmos">RuntimeGizmos</a></td>
<td>Runtime debugging and visualization gizmos</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add RuntimeGizmos</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SnapCloudExamples/Assets/AssetImage/SnapCloudExamples.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SnapCloudExamples">SnapCloudExamples</a></td>
<td>Supabase auth, database, storage, and real-time examples for Spectacles</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SnapCloudExamples</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SnapDecorators/Assets/AssetImage/SnapDecorators.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SnapDecorators">SnapDecorators</a></td>
<td>TypeScript decorators for components, events, and dependency injection</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SnapDecorators</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Solvers/Assets/AssetImage/Solvers.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Solvers">Solvers</a></td>
<td>Mathematical solvers and computation utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add Solvers</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Spectacles3DHandHints/Assets/AssetImage/Spectacles3DHandHints.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Spectacles3DHandHints">Spectacles3DHandHints</a></td>
<td>3D hand tracking and gesture recognition</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add Spectacles3DHandHints</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SpectaclesInteractionKitExamples/Assets/AssetImage/SpectaclesInteractionKitExamples.svg.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SpectaclesInteractionKitExamples">SpectaclesInteractionKitExamples</a></td>
<td>SIK and UIKit example scenes, scroll views, and interaction patterns</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SpectaclesInteractionKitExamples</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SpectaclesNavigationKit/Assets/AssetImage/SpectaclesNavigationKit.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SpectaclesNavigationKit">SpectaclesNavigationKit</a></td>
<td>Spatial navigation framework and components</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SpectaclesNavigationKit</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SpectaclesShaderLibrary/Assets/AssetImage/SpectaclesShaderLibrary.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SpectaclesShaderLibrary">SpectaclesShaderLibrary</a></td>
<td>Collection of shaders for AR rendering</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SpectaclesShaderLibrary</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SupabaseClient/Assets/AssetImage/SupabaseClient.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SupabaseClient">SupabaseClient</a></td>
<td>Supabase integration and client utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SupabaseClient</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SurfacePlacement/Assets/AssetImage/SurfacePlacement.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SurfacePlacement">SurfacePlacement</a></td>
<td>Surface detection and object placement utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add SurfacePlacement</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/VolumetricLine/Assets/AssetImage/VolumetricLine.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/VolumetricLine">VolumetricLine</a></td>
<td>Volumetric line rendering components</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add VolumetricLine</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/WorldQueryHit/Assets/AssetImage/WorldQueryHitExample.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/WorldQueryHit">WorldQueryHit</a></td>
<td>World space query and hit detection utilities</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add WorldQueryHit</code></td>
</tr>
</tbody>
</table>

---

## Context Repository

Developer resources, documentation, and curated guides for Spectacles development. This repository serves as context for AI systems to understand Spectacles development patterns, APIs, and best practices.

<table>
<tbody>
<tr>
<th>Title</th>
<th>Description</th>
</tr>
<tr>
<td align="center"><a href="https://github.com/specs-devs/context/tree/main/docs">docs</a></td>
<td>Comprehensive documentation including guides, tutorials, best practices, and API references</td>
</tr>
<tr>
<td align="center"><a href="https://github.com/specs-devs/context/tree/main/frameworks">frameworks</a></td>
<td>Reserved on the public mirror; use Lens Studio and published packages for framework sources.</td>
</tr>
<tr>
<td align="center"><a href="https://github.com/specs-devs/context/tree/main/packages">packages</a></td>
<td>Complete package library with all reusable components and utilities</td>
</tr>
<tr>
<td align="center"><a href="https://github.com/specs-devs/context/tree/main/samples">samples</a></td>
<td>Collection of sample projects and example implementations</td>
</tr>
</tbody>
</table>

---

<div align="center">

### Built 👻 with by the Spectacles team

</div>
