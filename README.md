# Keypoints Detection by YOLOv11
Keypoints Detection for markerpens using YOLOv11 Deep Learning Algorithm

## Dataset
- Marker Pens (Custom)

Annotation Type - Keypoints with Bounding Boxes

Classes &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &ensp; - ROI with 2 keypoints, ROI with 3 keypoints

## Methodology
- YOLOv11 Pose estimation/Keypoints Detection Model
- YOLO11m for 2 keypoints, YOLO11l for 3 keypoints
- PyTorch, IPython.display
- Google Colab, Roboflow

## Results
- ### Validation of trained models

|          | P     | R     | F1    | mAP   |
| ---------| ----- | ----- | ----- | ----- |
| 3P model | 0.999 | 1     | 0.999 | 0.995 |
| 2P model | 0.852 | 0.875 | 0.863 | 0.836 |

---
* Example images results in `yolov11-keypoints.ipynb`
