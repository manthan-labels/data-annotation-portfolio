# Video Annotation Project – Traffic Dataset (CVAT)

## Project Overview
This project contains **video annotations across 50 frames** from a dashcam sequence.  
Annotations were created using **[CVAT](https://cvat.ai/)** with **multi-class bounding boxes** for the following object categories:
- **Car**
- **Bike**
- **Pedestrian**

The dataset is designed for **computer vision tasks** such as:
- Object detection
- Multi-class classification
- Tracking across frames

---

## Tools & Workflow
- **Annotation Tool:** CVAT (interpolation + manual correction for accuracy)  
- **Classes:** `car`, `bike`, `pedestrian`  
- **Frames Annotated:** 50 (dense traffic sequence)  
- **Annotation Method:**  
  - Keyframe labeling with interpolation for efficiency  
  - Bounding boxes adjusted for occlusion and partial visibility  
  - Consistent class naming across all frames