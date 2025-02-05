# The Ancient Egypt VR Experience

> **Step into the past and explore a historically accurate ancient Egyptian tomb in immersive virtual reality.**

---

## 1. Project Overview

- **Archaeologically Accurate**  
  Meticulous research brings Egyptian art, symbols, and architecture to life based on museum archives and scholarly papers.

- **Immersive Educational Content**  
  Learn about ancient Egyptian culture, hieroglyphics, and burial rituals through interactive exhibits and in-world prompts.

- **Multiple VR Platforms**  
  Seamlessly supports HTC Vive, Oculus Rift, and Windows Mixed Reality for broad accessibility.

- **High-Fidelity Visuals**  
  Using advanced texturing and photogrammetry (if applicable) to ensure a lifelike environment.

---

## 2. Key Technologies Used

- **Unity 3D** – Core engine for real-time 3D rendering and VR development.  
- **C#** – Scripting language for game logic and interactivity.  
- **SteamVR / Oculus SDK** – Integration for smooth performance on VR headsets.  
- **Photogrammetry & 3D Scanning** *(if applicable)* – Bring realistic, high-resolution 3D assets to life.  
- **Windows Mixed Reality** – Additional compatibility layer for an expanded range of headsets.

---

## 3. Installation & Quick Setup

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-repo-url.git

2. **Open Project in Unity**  
   Launch the Unity Editor and select the cloned project folder.

3. **Install Dependencies**  
   When prompted, import required packages (SteamVR, Oculus Integration, etc.).

4. **Configure XR Settings**  
   In **Project Settings → XR Plugin Management**, enable the VR headsets you want to support.

5. **Build & Run**  
   Press **Build and Run** in Unity to launch the VR experience on your selected device.


## 4. Features & Detailed Functionality

### Archaeological Research & Accuracy
- **Consultation with Egyptology Experts**: Ensures authentic tomb layouts and hieroglyphs.  
- **References to Museum Archives & Historical Papers**: Provides a solid foundation for artifact design and placement.

### Artistic & Visual Design
- **Hand-Painted & Scanned Textures**: Replicates original murals and carvings with stunning detail.  
- **Immersive Lighting**: Evokes the atmosphere of torchlit corridors.

### Interactive Learning Modules
- **Artifact Inspection**: Pick up and examine objects up close; learn their backstory.  
- **Hieroglyphic Puzzles**: Engage with deciphering tasks to uncover hidden messages.  
- **Guided & Free-Roam Modes**: Toggle narration and educational prompts based on your preference.

## 5. Project Structure

```bash
/Assets
   ├─ Scenes           # Unity Scenes (tomb environments)
   ├─ Scripts          # C# scripts for VR interactions and game logic
   ├─ Models           # 3D models of artifacts, walls, statues, etc.
   ├─ Textures         # High-resolution textures for murals and environments
   └─ Audio            # Sound effects, ambient music, and narration
```

   # Dependencies and package references
TBU
/ProjectSettings
   # Unity configuration files
TBU

## 6. Usage Instructions

### Movement & Controls
- Use VR controllers to teleport or smoothly navigate the tomb corridors.  
- Grip or trigger buttons to interact with objects.

### Inspection Mode
- Grab artifacts for up-close examination; pop-up texts or narration may reveal historical details.

### Educational Prompts
- Toggle guided commentary or roam freely for a purely exploratory experience.

### Puzzle Mechanics
- Solve hieroglyphic riddles and lever-based interactions to unlock new areas or discover hidden secrets.

---

## 7. Contribution Guidelines

### Branching & Pull Requests
- Use feature branches for new additions; submit pull requests to the `main` or `develop` branch for review.

### Coding Standards
- Follow standard C# conventions (e.g., Microsoft .NET style guidelines).

### Issue Reporting
- Use GitHub Issues to log bugs, feature requests, or general improvements.


## BSD 3-Clause License

Copyright (c) [2025],
Berkeley Institute for Data Science (BIDS), University of California, Berkeley
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, 
are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, 
   this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice, 
   this list of conditions and the following disclaimer in the documentation 
   and/or other materials provided with the distribution.
3. Neither the name of the Berkeley Institute for Data Science (BIDS), 
   the University of California, nor the names of its contributors may be used 
   to endorse or promote products derived from this software without specific 
   prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" 
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, 
THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE 
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE 
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; 
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON 
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT 
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS 
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

