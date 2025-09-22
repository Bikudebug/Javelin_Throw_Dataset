# Biomechanical-phase based Temporal Segmentation in Sports Videos: a Demonstration on Javelin-Throw
![JavelinThrowNeerajChopraGIF (2)](https://github.com/user-attachments/assets/617f6561-6555-4374-8ab4-474a01e71ccf)

# Javelin Throw Action Dataset

This repository hosts the **Javelin Throw Action Dataset**, which contains synchronized **video files**, **skeleton pose data**, and **annotated action phase data** for javelin throw analysis.  
The dataset is designed to support research in **sports action segmentation**, **pose estimation**, and **phase detection**.

---

## 📂 Dataset Structure

The dataset is organized into the following components:

| Component | Description | Link |
|-----------|-------------|------|
| 🎥 **Video Files** | Original javelin throw videos in `.mp4` format. Each file is named `vid_<index>.mp4`. | [Video Files Link](https://drive.google.com/file/d/1fKfZNCHdr3NK7Ppnfcb3oV-57pTRH9ys/view?usp=sharing) |
| 🦴 **Skeleton Data** | 2D pose skeleton data extracted from the videos, using MMPose. Stored in `.json` format. | [Skeleton Data Link](https://drive.google.com/file/d/1DM9kKhr7CwC61Df60mzRVP6s_bcI8XP8/view?usp=sharing)|
| 📝 **Annotated Data** | Frame-level annotations of javelin throw phases: *Steps*, *Drive*, *Throw*, *Recovery*. Stored in `.csv` or `.json` format. | [Annotated Data Link](https://your-link-here.com) |

---

## 📑 File Naming Convention

- **Video Files**: `vid_<index>.mp4` (e.g., `vid_0.mp4`, `vid_1.mp4`…)  
- **Skeleton Files**: `skeleton_<index>.json` or `.npz` corresponding to each video file.  
- **Annotation Files**: `annotation_<index>.csv` with labeled frame numbers for each phase.  

This naming convention ensures easy mapping between video, skeleton, and annotation files.

---

## 📝 Annotation Format

Each annotation file contains frame-level phase information:
```csv
frame,phase
0,steps
1,steps
32,drive
45,throw
55,recovery
