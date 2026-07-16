# Medical Computer Vision Laboratory

> An open-source teaching laboratory for learning Computer Vision through medical imaging, 3D reconstruction, and interactive Google Colab experiments.

---

## Overview

Medical Computer Vision Laboratory is an open-source educational project designed for undergraduate and graduate Computer Vision courses.

Instead of relying on synthetic examples, this repository introduces students to modern computer vision techniques using real medical-inspired datasets and interactive laboratory exercises.

Students learn fundamental concepts including:

- Image Processing
- Feature Detection
- Feature Matching
- Camera Geometry
- Structure from Motion (SfM)
- 3D Reconstruction
- Region Analysis
- Image Segmentation

All experiments are designed to run inside Google Colab with minimal setup.

---

## Educational Philosophy

The laboratory follows a project-based learning approach.

Students receive only a collection of images acquired from different viewpoints of a real 3D anatomical model.

Their task is to reconstruct the scene, analyze it, and identify abnormal regions using classical computer vision algorithms.

The original 3D model is intentionally hidden from students to simulate a real-world reconstruction problem.

---

## Laboratory Workflow

```text
3D Anatomical Model
        │
        ▼
Virtual Camera Rendering
        │
        ▼
Image Dataset
        │
        ▼
Feature Detection
        │
        ▼
Feature Matching
        │
        ▼
Structure from Motion
        │
        ▼
Sparse 3D Reconstruction
        │
        ▼
Region Analysis
        │
        ▼
Segmentation & Masking
```

---

## Laboratory Modules

| Lab | Topic |
|------|------|
| Lab00 | Introduction |
| Lab01 | Image Processing |
| Lab02 | Feature Detection |
| Lab03 | Feature Matching |
| Lab04 | Structure from Motion |
| Lab05 | 3D Analysis |
| Lab06 | Final Project |

---

## Repository Structure

```text
Medical-Computer-Vision-Laboratory/

docs/
instructor/
student/
assets/
scripts/
```

---

## Instructor Version

The instructor edition contains

- Original 3D anatomical models
- Rendering scripts
- Camera trajectories
- Dataset generation tools
- Laboratory solutions

---

## Student Version

The student edition contains only

- Image datasets
- Google Colab notebooks
- Laboratory exercises
- Reports

Students never receive the original 3D model.

---

## Technologies

- Python
- OpenCV
- NumPy
- Open3D
- Google Colab
- Matplotlib

---

## Learning Outcomes

After completing this laboratory students will be able to

- Process medical images
- Detect and match image features
- Estimate camera motion
- Reconstruct sparse 3D scenes
- Analyze abnormal regions
- Generate segmentation masks
- Apply computer vision techniques to medical applications

---

## Roadmap

- [ ] Instructor rendering pipeline
- [ ] Student laboratory notebooks
- [ ] Google Colab support
- [ ] Automatic dataset generator
- [ ] Medical image segmentation module
- [ ] Interactive 3D visualization
- [ ] Additional anatomical datasets

---

## Contributing

Contributions are welcome.

Please open an Issue before submitting a Pull Request.

---

## License

This project is released under the MIT License.

---

## Acknowledgements

Some anatomical models used in this laboratory are provided by the NIH 3D Print Exchange for educational purposes.

https://3d.nih.gov/
