# McgillXR

A Mixed/Extended Reality (XR) project developed at McGill University. This repository contains the source code, assets, and documentation for the McgillXR experience.

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## About

McgillXR is an extended reality application built to deliver immersive and interactive experiences. The project leverages modern XR frameworks and tools to create engaging virtual, augmented, or mixed reality environments.

---

## Features

- 🥽 Immersive XR environment
- 🎮 Interactive user controls
- 🏫 McGill University themed content
- 🔧 Modular and extensible architecture
- 📱 Cross-platform support

---

## Getting Started

Follow the instructions below to get a local copy of the project up and running.

### Prerequisites

Ensure you have the following installed:

- [Unity](https://unity.com/) (recommended version: 2022.x LTS or later)
- XR Plugin Management (installable via Unity Package Manager)
- Compatible XR headset or emulator (e.g., Oculus, HTC Vive, HoloLens)
- Git

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/zairil10/McgillXR.git
   cd McgillXR
   ```

2. **Open the project in Unity:**
   - Launch Unity Hub
   - Click **Add** and select the cloned project folder
   - Open the project with the appropriate Unity version

3. **Install dependencies:**
   - Go to `Window > Package Manager`
   - Install required XR packages (XR Interaction Toolkit, XR Plugin Management, etc.)

4. **Configure XR settings:**
   - Navigate to `Edit > Project Settings > XR Plug-in Management`
   - Enable the appropriate XR platform (e.g., Oculus, OpenXR)

---

## Usage

1. Connect your XR headset or enable the XR emulator.
2. Press **Play** in the Unity Editor to launch the experience.
3. For a standalone build:
   - Go to `File > Build Settings`
   - Select your target platform and click **Build and Run**

---

## Project Structure

```
McgillXR/
├── Assets/
│   ├── Scenes/          # Unity scenes
│   ├── Scripts/         # C# scripts
│   ├── Prefabs/         # Reusable prefabs
│   ├── Materials/       # Materials and shaders
│   └── Resources/       # Runtime resources
├── Packages/            # Unity package dependencies
├── ProjectSettings/     # Unity project settings
└── README.md
```

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## License

This project is licensed under the [MIT License](LICENSE).

---

> Developed with ❤️ at McGill University
