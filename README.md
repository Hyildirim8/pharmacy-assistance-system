# Integrated Pharmacy Assistance System

This repository brings together the three modules developed for the autonomous
pharmacy assistance graduation project. Each root-level folder is linked to its
independent source repository as a Git submodule.

| Module | Description |
|---|---|
| [`robot`](robot) | ROS 2, SLAM Toolbox, Nav2, mecanum drive, sensors, and physical robot benchmarks |
| [`medication-recognition`](medication-recognition) | Eight-class medication package recognition and multi-model CNN/ViT benchmarks |
| [`face-recognition`](face-recognition) | Face enrollment, open-set recognition, unknown-person rejection, and benchmark outputs |

## Clone all modules

```bash
git clone --recurse-submodules https://github.com/Hyildirim8/pharmacy-assistance-system.git
```

For an existing clone:

```bash
git submodule update --init --recursive
```
