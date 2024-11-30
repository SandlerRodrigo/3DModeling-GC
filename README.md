
# 3D Modeling - Graphics Computation Project

This project demonstrates a 3D modeling application using OpenGL and GLUT. It includes interactive features like camera movement, player actions, and dynamic adjustments for shooting mechanics.

---

## ✨ Features

- **3D Models:** Visualize and interact with 3D objects.
- **Camera Control:** Navigate the scene using keyboard inputs.
- **Player Mechanics:** Move, aim, and shoot with the player-controlled cannon.
- **Customizable Shots:** Adjust shot speed and trajectory.

---

## 📋 Requirements

To compile and run the project, you need:
- A C++ compiler supporting C++11 or later.
- **OpenGL** and **GLUT** libraries.
- **SOIL (Simple OpenGL Image Library)** for texture handling. (Already in the project root)

---

## 📁 File Structure

```
3DModeling-GC/
├── assets/            # Textures and 3D models
├── include/           # Header files for modular components
├── lib/               # SOIL library for image processing
├── src/               # Source code for application logic
├── Makefile           # Build instructions
└── Trabalho 2 Computação Gráfica.pdf # Original project documentation
```

---

## ⚙️ Compilation

Use the provided `Makefile` to compile the project:

```bash
make
```

The generated executable will be in the root project directory.

---

## ▶️ Running the Project

After compilation, run the executable:

```bash
./bin/3DModeling-GC
```

---

## 🎮 Controls

| **Key**   | **Action**                                 |
|-----------|-------------------------------------------|
| `W`       | Move forward                              |
| `S`       | Move backward                             |
| `A`       | Look left                                 |
| `D`       | Look right                                |
| `Q`       | Raise the player's cannon                 |
| `E`       | Lower the player's cannon                 |
| Spacebar  | Fire a shot                               |
| `[`       | Decrease shot speed                       |
| `]`       | Increase shot speed                       |

---

## 🖼️ Assets

The project includes the following resources:
- **Textures:** Located in `assets/textures/`, including `grass.png` and `brick.png`.
- **3D Models:** Located in `assets/models/`, such as `tank.obj`, `tree.obj`, and `star.obj`.

---

## 📜 License

This project is distributed under the MIT License. See `LICENSE` for details.

---
