<div align="center">

<img src="https://raw.githubusercontent.com/specs-devs/.github/main/profile/SPECS.jpeg" width="600" height="auto" align="center">

# SPECS

**The official GitHub for SPECS**

*Where you can find the best projects to start your AR developer journey. Let's build the future.*

[![Website](https://img.shields.io/badge/-Website-1a1a1a?style=flat&labelColor=1a1a1a&logo=google-chrome&logoColor=white)](https://www.spectacles.com/)
[![Reddit](https://img.shields.io/badge/-Reddit-ff4500?style=flat&labelColor=ff4500&logo=reddit&logoColor=white)](https://www.reddit.com/r/Spectacles/)
[![Twitter](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white)](https://twitter.com/Spectacles)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat&labelColor=E4405F&logo=instagram&logoColor=white)](https://www.instagram.com/specsfordevs/)
[![YouTube](https://img.shields.io/badge/YouTube-ff0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/@specsfordevs)
[![Developers](https://img.shields.io/badge/-Developers-1a1a1a?style=flat&labelColor=1a1a1a&logo=readthedocs&logoColor=white)](https://developers.specs.com/)
[![Spectacles Docs](https://img.shields.io/badge/-Spectacles%20Docs-FFFC00?style=flat&labelColor=FFFC00&logo=snapchat&logoColor=black)](https://developers.snap.com/spectacles/home)

---

</div>

## Getting Started

Before you begin developing for SPECS, make sure you have the required tools installed:

**Required Software:**
- **[Lens Studio](https://ar.snap.com/spectacles)** - Snap's free AR development platform for creating Spectacles experiences
- **[Spectacles App (Android)](https://play.google.com/store/apps/details?id=com.snap.spectacles.app&hl=en_US)** - Companion app for Android devices
- **[Spectacles App (iOS)](https://apps.apple.com/us/app/spectacles-by-snap-inc/id6502670261)** - Companion app for iOS devices

---

## About

SPECS is the official GitHub organization for SPECS development resources. We provide open-source tools, frameworks, templates, and comprehensive documentation to help developers build amazing AR experiences for Spectacles. 
> [!IMPORTANT]
> **Spectacles (2024) is supported only on `5.15.4`.** Use the `5.15.4` branch / release of each repo.
> **Everything `5.22.0`+ targets SPECS 27.** Redirect links here assume `main` (5.22.0+) and won't work with Spectacles (2024).

Whether you're creating your first AR lens or developing complex spatial applications, we offer the resources and community support you need to succeed.

---

## Samples Repository

Ready-to-use project templates and sample applications demonstrating Spectacles capabilities. Clone individual projects using sparse checkout:

<table>
<tbody>
<tr>
<th>Preview</th>
<th>Title</th>
<th>Description</th>
<th>Clone Command</th>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/AI%20Playground/README-ref/sample-list-ai-playground-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/AI%20Playground">AI Playground</a></td>
<td>Sample project for AI in using Specs Remote Service Gateway.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "AI Playground"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Crop/README-ref/sample-list-crop-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Crop">Crop</a></td>
<td>Sample project showing how to "crop" the environment using hand gesture.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Crop"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Depth%20Cache/README-ref/sample-list-depth-cache-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Depth%20Cache">Depth Cache</a></td>
<td>Cache depth frames for pixel-to-3D projection with cloud-based vision models.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Depth Cache"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/AI%20Music%20Gen/README-ref/sample-list-ai-music-gen-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/AI%20Music%20Gen">AI Music Gen</a></td>
<td>Generate AI music using Google's Lyria model. Combine genres, vibes, and instruments to create custom music tracks with 3D visualizations.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "AI Music Gen"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Agent%20Manager/README-ref/agent-multitask.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Agent%20Manager">Agent Manager</a></td>
<td>Multi-agent assistant hub for Specs—run and manage multiple AI agents with text and voice input.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Agent Manager"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Fetch/README-ref/sample-list-fetch-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Fetch">Fetch</a></td>
<td>Sample project using the Specs Fetch API.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Fetch"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Essentials/README-ref/sample-list-essentials-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Essentials">Essentials</a></td>
<td>Collection of foundational concepts for creating lenses in Lens Studio.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Essentials"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Spatial%20Image/README-ref/sample-list-spatial-image-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Spatial%20Image">Spatial Image</a></td>
<td>Convert your 2D images to 3D.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Spatial Image"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Throw%20Lab/README-ref/sample-list-throw-lab-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Throw%20Lab">Throw Lab</a></td>
<td>Sample project demonstrating realistic throwing mechanics in AR.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Throw Lab"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Voice%20Playback/README-ref/sample-list-voice-playback-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Voice%20Playback">Voice Playback</a></td>
<td>Sample project for recording and playing back audio on Specs.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Voice Playback"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Path%20Pioneer/README-ref/sample-list-path-pioneer-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Path%20Pioneer">Path Pioneer</a></td>
<td>Sample project for path creation and path walking experience.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Path Pioneer"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Specs%20Mobile%20Kit/README-ref/sample-list-mobile-kit-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Specs%20Mobile%20Kit">Specs Mobile Kit</a></td>
<td>SDK for seamless communication between mobile applications and Lenses running on Specs via BLE.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Specs Mobile Kit"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/DJ%20Specs/README-ref/sample-list-dj-specs-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/DJ%20Specs">DJ Specs</a></td>
<td>Interactive DJ turntable experience with realistic vinyl physics and multi-track audio mixing.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "DJ Specs"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Custom%20Locations/README-ref/sample-list-custom-locations-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Custom%20Locations">Custom Locations</a></td>
<td>Map real life areas and create AR experiences around those locations.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Custom Locations"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Navigation%20Kit/README-ref/sample-list-navigation-kit-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Navigation%20Kit">Navigation Kit</a></td>
<td>An example project for indoors or outdoors navigation.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Navigation Kit"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Sync%20Kit%20Basic%20Example/README-ref/sample-list-spectacles-sync-kit-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Sync%20Kit%20Basic%20Example">Specs Sync Kit</a></td>
<td>Minimal example of Specs Sync Kit transform synchronization across Connected Lenses.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/samples.git<br>cd samples && git sparse-checkout add "Sync Kit Basic Example"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/samples/main/Snap%20Cloud%20World%20Kindness%20Day/README-ref/sample-list-world-kindness-day-rounded-edges.gif" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/samples/tree/main/Snap%20Cloud%20World%20Kindness%20Day">Snap Cloud World Kindness Day</a></td>
<td>Demonstrating Snap Cloud integration with real-time database updates and a companion web app.</td>
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
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/RemoteServiceGateway/Assets/AssetImage/RemoteServiceGateway.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/RemoteServiceGateway">Remote Service Gateway</a></td>
<td>A package that provides a set of tools that allow to publish lenses with access to user-sensitive data.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "RemoteServiceGateway"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SpecsNavigationKit/Assets/AssetImage/SpecsNavigationKit.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SpecsNavigationKit">Specs Navigation Kit</a></td>
<td>Set of components designed to simplify the development of navigation experiences for Specs.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SpecsNavigationKit"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/CommerceKit/Assets/AssetImage/CommerceKit.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/CommerceKit">CommerceKit (Closed Beta)</a></td>
<td>Framework for handling in-app purchases for non-consumable items in Specs.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "CommerceKit"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SpecsInteractionKitExamples/Assets/AssetImage/SpecsInteractionKitExamples.svg.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SpecsInteractionKitExamples">Specs Interaction Kit Examples</a></td>
<td>Example scenes and prefabs for SpectaclesInteractionKit and SpectaclesUIKit, including Rocket Workshop and UI starter patterns.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SpecsInteractionKitExamples"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/AiPreviewAgentInspect/Assets/AssetImage/AiPreviewAgentInspect.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/AiPreviewAgentInspect">AI Preview Agent - Inspect</a></td>
<td>Lens-side bridge that lets an external AI agent observe a running Lens through live scene queries and orthographic render captures.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "AiPreviewAgentInspect"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/AiPreviewAgentInteract/Assets/AssetImage/AiPreviewAgentInteract.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/AiPreviewAgentInteract">AI Preview Agent - Interact</a></td>
<td>Lets an external AI agent drive a running Lens by synthesizing pinch, poke, and drag hand interactions for end-to-end agent verification.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "AiPreviewAgentInteract"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SupabaseClient/Assets/AssetImage/SupabaseClient.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SupabaseClient">Supabase Client</a></td>
<td>Client library for connecting to Supabase backend infrastructure.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SupabaseClient"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SnapCloudExamples/Assets/AssetImage/SnapCloudExamples.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SnapCloudExamples">Snap Cloud Examples</a></td>
<td>Collection of examples demonstrating Supabase integration for authentication, real-time data, and cloud storage.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SnapCloudExamples"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Specs3DHandHints/Assets/AssetImage/Specs3DHandHints.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Specs3DHandHints">Specs 3D Hand Hints</a></td>
<td>Suite of animated Hand Gestures Hints.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "Specs3DHandHints"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/InteractableHelper/Assets/AssetImage/InteractableHelper.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/InteractableHelper">Interactable Helper</a></td>
<td>Low to medium fidelity prototyping tool for Specs Interaction Kit components without code.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "InteractableHelper"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/FunctionCallHelper/Assets/AssetImage/FunctionCallHelper.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/FunctionCallHelper">Function Call Helper</a></td>
<td>System for exposing function callbacks in the inspector, allowing you to configure and trigger script functions through UI buttons.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "FunctionCallHelper"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/FaceMesh/Assets/AssetImage/FaceMesh.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/FaceMesh">Face Mesh</a></td>
<td>Face mesh tracking setup with customizable materials and transform matching for smooth tracking motion.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "FaceMesh"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/BodyMesh/Assets/AssetImage/BodyMesh.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/BodyMesh">Body Mesh</a></td>
<td>Body mesh tracking and rigging utilities for full-body AR experiences.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "BodyMesh"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/HandAttacher/Assets/AssetImage/HandAttacher.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/HandAttacher">Hand Attacher</a></td>
<td>Attach objects to hand joints in world space with customizable offsets and smooth interpolation.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "HandAttacher"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/ReachyReceiver/Assets/AssetImage/ReachyReceiver.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/ReachyReceiver">Reachy Receiver</a></td>
<td>Integration for Reachy humanoid robot with WebSocket streaming.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "ReachyReceiver"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/MocopiReceiver/Assets/AssetImage/MocopiReceiver.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/MocopiReceiver">Mocopi Receiver</a></td>
<td>Full-body motion capture integration for Sony mocopi sensors with WebSocket streaming and automatic bone mapping.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "MocopiReceiver"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/WebSocketExamples/Assets/AssetImage/WebsocketExamples.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/WebSocketExamples">WebSocket Examples</a></td>
<td>WebSocket examples for real-time data exchange including TextEcho, IMUData, and IMUCube.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "WebSocketExamples"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Instantiation/Assets/AssetImage/Instantiation.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Instantiation">Instantiation</a></td>
<td>Examples for dynamic object creation.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "Instantiation"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Solvers/Assets/AssetImage/Solvers.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Solvers">Solvers</a></td>
<td>Collections of spatial behaviors for Spatial UI or scene objects.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "Solvers"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/AccessComponents/Assets/AssetImage/AccessComponents.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/AccessComponents">Access Components</a></td>
<td>Collection of scripts to showcase how to reference and access classes.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "AccessComponents"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/WorldQueryHit/Assets/AssetImage/WorldQueryHitExample.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/WorldQueryHit">World Query Hit - Spawn On Surface</a></td>
<td>Performs hit tests for real-world surfaces.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "WorldQueryHit"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SurfacePlacement/Assets/AssetImage/SurfacePlacement.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SurfacePlacement">Surface Placement</a></td>
<td>Detects and recognizes real-world surfaces.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SurfacePlacement"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SnapDecorators/Assets/AssetImage/SnapDecorators.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SnapDecorators">Snap Decorators</a></td>
<td>TypeScript decorators for simplified event binding and dependency injection to reduce boilerplate code.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SnapDecorators"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/Utilities/Assets/AssetImage/Utilities.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/Utilities">Utilities</a></td>
<td>Comprehensive utility library for scene object management, math operations, animations, and type conversions.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "Utilities"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/AnimationExamples/Assets/AssetImage/AnimationExamples.svg" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/AnimationExamples">Animation Examples</a></td>
<td>Native AnimationPlayer tween examples — scale, opacity, push-Z, squish, and timeline-driven animations driven from script.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "AnimationExamples"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/RuntimeGizmos/Assets/AssetImage/RuntimeGizmos.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/RuntimeGizmos">Runtime Gizmos</a></td>
<td>Collections of line based tools for debugging or visualization.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "RuntimeGizmos"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/MarkerTrackingHelper/Assets/AssetImage/MarkerTrackerHelper.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/MarkerTrackingHelper">Marker Tracking Helper</a></td>
<td>Provides Marker Tracking Examples.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "MarkerTrackingHelper"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/VolumetricLine/Assets/AssetImage/VolumetricLine.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/VolumetricLine">Volumetric Line</a></td>
<td>Advanced volumetric line rendering system for 3D graphics.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "VolumetricLine"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/SpecsShaderLibrary/Assets/AssetImage/SpecsShaderLibrary.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/SpecsShaderLibrary">Specs Shader Library</a></td>
<td>Collection of seven optimized shaders designed to enhance power efficiency without sacrificing visual quality.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "SpecsShaderLibrary"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/EasyTeleprompter/Assets/AssetImage/EasyTeleprompter.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/EasyTeleprompter">Easy Teleprompter</a></td>
<td>Teleprompter lens for rehearsal and live public speaking with text display in field of view.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "EasyTeleprompter"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/GuidedInstructions/Assets/AssetImage/GuidedInstructions.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/GuidedInstructions">Guided Instructions</a></td>
<td>Voice-driven, AI-assisted guided AR experiences: speech, depth, Gemini integration, and world-space UI.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "GuidedInstructions"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/CompositeCameraTexture/Assets/AssetImage/CompositeCameraTexture.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/CompositeCameraTexture">Composite Camera Texture</a></td>
<td>Advanced camera texture compositing and blending system.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "CompositeCameraTexture"</code></td>
</tr>
<tr>
<td align="center"><img src="https://raw.githubusercontent.com/specs-devs/packages/main/CropCameraTexture/Assets/AssetImage/CropCameraTexture.png" width="200"/></td>
<td align="center"><a href="https://github.com/specs-devs/packages/tree/main/CropCameraTexture">Crop Camera Texture</a></td>
<td>Camera texture cropping and region selection tools.</td>
<td><code>git clone --filter=blob:none --sparse https://github.com/specs-devs/packages.git<br>cd packages && git sparse-checkout add "CropCameraTexture"</code></td>
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

### Maintained with 👽 by the SPECS Team

</div>
