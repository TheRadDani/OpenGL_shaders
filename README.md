# OpenGL_shaders

A minimal cross-platform OpenGL learning project demonstrating shader setup, VAO/VBO usage, and rendering a simple triangle using GLFW + GLAD.

## Demo
Add a short GIF or screenshot showing the rendered triangle (`demo.gif` or `screenshot.png`).

## Features
- Modern OpenGL (core profile, GLSL 330)
- Single-file minimal example (`main.cpp`) showing:
  - shader creation & linking
  - VAO/VBO setup
  - render loop with GLFW
- Build instructions for Visual Studio 2026

## Prerequisites
- Windows 10/11 or Linux/macOS
- Visual Studio Community 2026 (18.4+) or compatible toolchain
- Dependencies:
  - GLFW
  - GLAD
  - OpenGL drivers

## Build (Visual Studio)
1. Open `GRAPH_CODING.sln` in Visual Studio.
2. Ensure GLFW and GLAD are added as project dependencies or set up as nuget/submodule.
3. In Project → Properties:
   - __Configuration__: Debug/Release
   - __VC++ Directories__: Add include/lib paths for GLFW/GLAD
   - __Linker -> Input__: Add `glfw3.lib`, `opengl32.lib` (Windows)
4. Build and run.

(If you prefer PowerShell 7 for scripts, install `pwsh` or update build scripts to use `powershell.exe`.)

## Project Layout
- `main.cpp` — minimal OpenGL triangle + shaders
- `README.md` — this file
- `LICENSE` — choose MIT or similar
- `assets/` — screenshots, demo GIFs

## How to contribute
- Fork, create a feature branch, open a PR
- Suggest enhancements: multiple shapes, color interpolation, keyboard controls, camera, basic lighting

## Roadmap / ideas
- Add indexed drawing (EBO)
- Add color vertex attribute and modify fragment shader for interpolation
- Toggle between wireframe and filled modes
- Add ImGui integration for runtime shader/uniform tweaking
- Small tutorial series (README + short articles) explaining each step

## Tags / topics (copy to repo Topics on GitHub)
openGL, graphics, learning, glfw, glad, shaders, cplusplus, tutorial, visual-studio

## License
MIT — see `LICENSE` file

## Contact
Open an issue or PR. Small, focused contributions welcome.