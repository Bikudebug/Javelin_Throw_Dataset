# Biomechanical-phase based Temporal Segmentation in Sports Videos: a Demonstration on Javelin-Throw
![Javelin Demo](https://github.com/Bikudebug/Javelin_Throw_Dataset/blob/main/side_by_side-ezgif.com-video-to-gif-converter.gif)

## Javelin Throw Dataset

This repository hosts the **Javelin Throw Action Dataset**, which contains synchronized **video files**, **skeleton pose data**, and **annotated action phase data** for javelin throw analysis.  
The dataset is designed to support research in **sports action segmentation**, **pose estimation**, and **phase detection**.

---

## 📂 Dataset Structure

The dataset is organized into the following components:

| Component | Description | Link |
|-----------|-------------|------|
| 🎥 **Video Files** | Original javelin throw videos in `.mp4` format. Each file is named `vid_<index>.mp4`. | [Video Files Link](https://drive.google.com/file/d/1fKfZNCHdr3NK7Ppnfcb3oV-57pTRH9ys/view?usp=sharing) |
| 🦴 **Skeleton Data** | 2D pose skeleton data extracted from the videos, using MMPose. Stored in `.json` format. | [Skeleton Data Link](https://drive.google.com/file/d/1DM9kKhr7CwC61Df60mzRVP6s_bcI8XP8/view?usp=sharing)|
| 📝 **Annotated Data** | Frame-level annotations of javelin throw phases: *Steps*, *Drive*, *Throw*, *Recovery*. Stored in `.json` format. | [Annotated Data Link](https://drive.google.com/file/d/1aaG10_POwS2g9pUnqjgpQrB1Kp9Htr9L/view?usp=sharing) |

---

## 📑 File Naming Convention

- **Video Files**: `vid_<index>.mp4` (e.g., `vid_0.mp4`, `vid_1.mp4`…)  
- **Skeleton Files**: `video_<index>.json` corresponding to each video file.  
- **Annotation Files**: `vid_<index>.json` with labeled frame numbers for each phase.  

This naming convention ensures easy mapping between video, skeleton, and annotation files.

---


