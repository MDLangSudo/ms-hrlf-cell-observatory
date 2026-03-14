# MS-HRLF Visualizer for Betzig Cell Observatory

**Multi-Scale Hierarchical Ridge Locking Filter (MS-HRLF)**

A free, browser-based tool for cleaning and exploring noisy 5D live-cell microscopy tracks (lysosome dynamics, organelle motion, etc.).

### Features
- Upload TrackMate, Nellie, or Ultrack CSV files (FRAME, X, Y, Z)
- Interactive 3D visualization with toggleable Coarse / Mid / Fine layers
- Preserves recursive fractalinear biological islands while removing photobleaching spikes and jitter
- Real-time Betti-0 metrics showing topological convergence
- One-click exports for TrackMate re-import and 5D VLM training

### Purpose
Built to help the Cell Observatory team turn chaotic 10⁷-DoF microscopy data into clean, hierarchical topological features — exactly the kind of pre-processing Eric Betzig highlighted as the missing piece for their Vision-Language Model.

### License
MIT License — free to use, modify, and integrate into any workflow.

Developed as part of the HRLF project (Grok & MD Lang, 2026) @rarelict on X.
