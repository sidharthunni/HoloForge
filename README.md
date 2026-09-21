# HoloForge: On-Device 3D Spatial Asset & Polygon Mesh Compiler

> **iQOO Hackathon 2026 (Hyderabad City Battle)**  
> **Track:** 07 - Open Innovation  
> **Target Hardware:** iQOO 15 (Snapdragon 8 Elite) & iQOO Neo Series  
> **Architecture:** 100% On-Device / Zero Cloud Dependency  

---

## Executive Summary
HoloForge is the world's first on-device 3D spatial asset and digital twin compiler engineered to run natively on mobile silicon. It scans physical objects via the phone camera and compiles them into production-ready, watertight 3D polygon meshes (`.OBJ` and `.GLTF`) in under 3 seconds—completely offline.

While Apple uses Spatial Video on iPhone Pro to capture creators with view-only stereoscopic content and Samsung's Galaxy AI relies on cloud text/image features, HoloForge outputs real, editable 3D CAD and game-ready polygon geometry.

---

## System Architecture Pipeline


1. **Capture Layer:** Continuous monocular camera stream with device IMU pose estimation.
2. **Silicon Acceleration:** Qualcomm Hexagon NPU executes INT8 quantized depth estimation at 60 FPS.
3. **C++ AST Geometry Compiler:** Compiles high-density point clouds into structured, watertight polygon meshes with collision wireframes in under 3 seconds.
4. **144Hz Spatial Viewport:** Accelerated by the dedicated Q-series display chip and 6K VC cooling chamber for zero-latency 6-DoF navigation.
5. **iQOO Office Kit Bridge:** High-bandwidth screen mirroring during the 16.5-hour Red Light phase, and instant USB-C export to PC CAD tools (Blender, Unity, 3D slicers) during Green Light.

---

## Market & Financial Impact for iQOO
- **$4.5 Billion Market Disruption:** Direct replacement for expensive standalone laser scanners ($1,000–$5,000).
- **$1.8B–$2.2B Turnover Uplift:** Moves iQOO Average Selling Price (ASP) from $400 into the $750+ premium tier by targeting 40M+ 3D printing makers, indie game developers, and e-commerce sellers.
- **Top 3 Positioning:** Gives iQOO an exclusive, non-copyable hardware-AI moat alongside Apple and Samsung.

---

## Event Compliance
- **16.5-Hour Red Light Ready:** Built from the ground up for phone-first development and verified HackTracker telemetry through the iQOO Office Kit.
- **Device Compatibility:** Optimized for the iQOO 15 flagship and backwards-compatible with the iQOO Neo series.

---

## Developer Credentials
- **Lead Developer:** Sidharth Unni (`sidharthunni`)
- **Track Record:** 
  - Smart India Hackathon (SIH) Finalist — DepthWizard (3D Vision & Depth Mapping)
  - SonoDent AI (DSOLVE) — Real-Time Clinical Digital Twin AST Compiler
