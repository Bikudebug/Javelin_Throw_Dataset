# Biomechanical-phase based Temporal Segmentation in Sports Videos: a Demonstration on Javelin-Throw
📄 **Paper available at:** https://ieeexplore.ieee.org/document/11264777

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

---
<table>
  <tr>
    <td width="10%" align="center">
      <img src="Figure/javelin-throw.gif" alt="Javelin Throw Animation" width="100">
    </td>
    <td width="70%">
      <h3>Throwing4 Dataset</h3>
      <p>
        This repository hosts the Throwing4 dataset, which contains synchronized RGB video files, skeleton pose data, and annotated action-phase data for elite athletics throwing analysis across javelin throw, discus throw, hammer throw, and shot put.
      </p>
    </td>
  </tr>
</table>

## **Citation**

If you use Throwing4 in your research, please cite:

```bibtex
@inproceedings{badatya2025biomechanical,
  title={Biomechanical-phase based temporal segmentation in sports videos: a demonstration on Javelin-throw},
  author={Badatya, Bikash Kumar and Baghel, Vipul and Amin, Jyotirmoy and Hegde, Ravi},
  booktitle={2025 IEEE International Workshop on Sport, Technology and Research (STAR)},
  pages={19--24},
  year={2025},
  organization={IEEE}
}

```


