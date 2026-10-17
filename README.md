# Awesome WebGPU Components

> Curated, link-verified building blocks for the WebGPU era: engines, toolkits, framework components and devtools.

WebGPU has quietly crossed from 'upcoming API' to the default rendering backend of the modern web: three.js and Babylon.js ship production WebGPU renderers, Rust's wgpu implements the spec natively, and a new generation of component libraries — shader effects you drop into React or Svelte, UI kits rendered inside 3D scenes, GPU charting — is being built on top. This list indexes those building blocks. Every link is checked to be live when this README is regenerated.

> [!NOTE]
> Compiled from public sources — no independent testing of the linked projects.

## Contents

- [🚀 Engines and Renderers with WebGPU Backends](#engines-and-renderers-with-webgpu-backends)
- [🔧 Low-Level Toolkits and GPU Utilities](#low-level-toolkits-and-gpu-utilities)
- [🧩 Framework Components](#framework-components)
- [🛠️ Developer Tools, Dashboards and Samples](#developer-tools-dashboards-and-samples)

## 🚀 Engines and Renderers with WebGPU Backends

Full rendering engines where WebGPU is either the native foundation or a production backend.

| Project | What it is | Tags |
|---|---|---|
| [three.js](https://github.com/mrdoob/three.js) | JavaScript 3D library whose renderer supports the WebGPU backend alongside WebGL. | `3d`, `renderer` |
| [Babylon.js](https://github.com/BabylonJS/Babylon.js) | Open game and rendering engine with a WebGPU engine backend and a node-based scene model. | `engine`, `3d` |
| [engine (PlayCanvas)](https://github.com/playcanvas/engine) | Web graphics runtime built on WebGL, WebGPU, WebXR and glTF for interactive 3D apps. | `engine`, `gltf` |
| [Orillusion](https://github.com/Orillusion/orillusion) | Pure Web3D rendering engine built entirely on WebGPU with a component-based ECS design. | `engine`, `ecs` |
| [spark](https://github.com/sparkjsdev/spark) | Advanced 3D Gaussian Splatting renderer for three.js, WebGPU-first. | `gaussian-splatting`, `renderer` |
| [maplibre-rs](https://github.com/maplibre/maplibre-rs) | Rust-based WebGPU map renderer for Web, Mobile and Desktop. | `maps`, `renderer` |
| [spektral](https://github.com/kaltwrk/spektral) | Minimalist framework for modern WebGPU visuals. | `framework` |
| [burrow](https://github.com/toji/burrow) | Toy WebGPU deferred renderer demonstrating a practical rendering architecture. | `renderer`, `deferred` |

## 🔧 Low-Level Toolkits and GPU Utilities

Implementations, wrappers and shader libraries one level below the frameworks.

| Project | What it is | Tags |
|---|---|---|
| [wgpu](https://github.com/gfx-rs/wgpu) | Cross-platform, safe, pure-Rust graphics API implementing the WebGPU spec for native and web. | `rust`, `graphics` |
| [wgpu-native](https://github.com/gfx-rs/wgpu-native) | Native WebGPU implementation based on wgpu-core, exposing WebGPU as a C library. | `native`, `bindings` |
| [gpu.cpp](https://github.com/AnswerDotAI/gpu.cpp) | A lightweight library for portable low-level GPU computation using WebGPU compute shaders. | `compute`, `cpp` |
| [TypeGPU](https://github.com/software-mansion/TypeGPU) | Modular toolkit for WebGPU with advanced type inference for writing shaders in TypeScript. | `typescript`, `toolkit` |
| [vgpu](https://github.com/vercel-labs/vgpu) | Modular cross-runtime WebGPU library for shaders, 3D scenes, GPU tensors and math. | `library`, `shaders` |
| [webgpu-utils](https://github.com/greggman/webgpu-utils) | Helpers for WebGPU covering pipeline setup, resources and common boilerplate. | `utils` |
| [lygia](https://github.com/patriciogonzalezvivo/lygia) | Granular multi-language shader library including WGSL for WebGPU pipelines. | `shaders`, `wgsl` |
| [pristine-grid-webgpu](https://github.com/toji/pristine-grid-webgpu) | A WebGPU implementation of the Pristine Grid shader technique. | `shaders`, `grid` |
| [webgpu-bundle-culling](https://github.com/toji/webgpu-bundle-culling) | WebGPU demonstration of frustum culling with render bundles through indirect instructions. | `culling`, `performance` |
| [watlas](https://github.com/toji/watlas) | Web port of XAtlas: mesh parameterization and UV unwrapping usable in WebGPU pipelines. | `geometry`, `utils` |

## 🧩 Framework Components

Drop-in components and bindings for React, React Native, react-three-fiber and friends.

| Project | What it is | Tags |
|---|---|---|
| [shaders (shader-effects-inc)](https://github.com/shader-effects-inc/shaders) | WebGPU shader-effect components for React, Vue, Svelte, Solid, JS and Framer. | `components`, `react` |
| [drei](https://github.com/pmndrs/drei) | Useful helper components and abstractions for react-three-fiber scenes. | `react`, `r3f` |
| [uikit](https://github.com/pmndrs/uikit) | User interface components for react-three-fiber rendered inside 3D scenes. | `ui`, `r3f` |
| [react (PlayCanvas)](https://github.com/playcanvas/react) | Build 3D apps with React using PlayCanvas engine components, with WebGPU support. | `react`, `3d` |
| [react-native-webgpu](https://github.com/wcandillon/react-native-webgpu) | React Native WebGPU bindings powered by Dawn. | `react-native`, `mobile` |
| [react-native-effects](https://github.com/blazejkustra/react-native-effects) | WebGPU-powered shader effects for React Native as drop-in components on a separate thread. | `react-native`, `shaders` |
| [r3f-webgpu-starter](https://github.com/ektogamat/r3f-webgpu-starter) | React Three Fiber WebGPU starter with post processing and a demo scene. | `react`, `starter` |
| [liquid-glass-studio](https://github.com/iyinchao/liquid-glass-studio) | Recreates Apple's Liquid Glass UI for the web, powered by WebGL2 and WebGPU. | `ui`, `effects` |

## 🛠️ Developer Tools, Dashboards and Samples

Inspectors, charting, official samples and tutorials for day-to-day WebGPU work.

| Project | What it is | Tags |
|---|---|---|
| [webgpu-samples](https://github.com/webgpu/webgpu-samples) | The official WebGPU samples repository demonstrating the API's features. | `samples`, `official` |
| [ChartGPU](https://github.com/ChartGPU/ChartGPU) | Open source, WebGPU-based charting library for high-performance data visualization. | `charts`, `dataviz` |
| [webgpu_inspector](https://github.com/brendan-duncan/webgpu_inspector) | Inspection debugger for WebGPU: inspect buffers, textures, pipelines and command streams. | `debugging`, `devtools` |
| [webgpu-claude-skill](https://github.com/dgreenheck/webgpu-claude-skill) | A Claude skill for developing WebGPU applications with Three.js. | `tooling`, `threejs` |
| [hello-triangle-webgpu](https://github.com/toji/hello-triangle-webgpu) | Well-commented hello triangle example for learning the WebGPU API. | `tutorial`, `example` |

---

## About this list

- **31** entries across **4** sections.
- Compiled from public sources; every linked project carries its own license.
- Last updated: **2026-10-17**.
- Data lives in `data/content.json` — this README is generated, do not edit by hand.

## License

The text and curation in this repository are licensed under CC BY 4.0. Linked projects keep their own licenses.
