# Urban Traffic Video Annotation (CVAT Project)

## Overview
This repository contains a **multi‑class traffic video annotation dataset** created using **CVAT**.  
The dataset focuses on **urban traffic scenes**, with bounding box annotations for **cars, bikes, and pedestrians**.  
It demonstrates **dense labeling** with ~350 annotations across 13 frames, making it a compact but high‑value showcase for object detection and tracking tasks.

---

## Dataset Details
- **Frames Annotated**: 13  
- **Total Annotations**: ~350 bounding boxes  
- **Classes**:  
  - `car`  
  - `bike`  
  - `pedestrian`  
- **Annotation Tool**: [CVAT](https://cvat.ai)  
- **Annotation Type**: Bounding boxes (with tracking across frames)  

---

## Export Formats
Annotations are provided in multiple formats:
- **Pascal VOC (XML)** → Native CVAT export  
- **YOLOv8 (TXT)** → Converted locally from VOC 