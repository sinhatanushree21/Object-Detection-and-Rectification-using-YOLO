# Object-Detection-and-Rectification-using-YOLO
This project demonstrates the use of the YOLO (You Only Look Once) algorithm for real-time object detection and subsequent rectification of detected objects in images.

🎯 Objectives
- Implement YOLO for detecting multiple objects in an image.
- Extract bounding boxes and class labels for each detected object.
- Apply rectification techniques (cropping, perspective correction, resizing) to standardize detected objects.
- Provide a reproducible workflow for integrating YOLO into downstream tasks such as classification, segmentation, or resource allocation
  
⚙️ Methodology
- Model Setup
- Load pretrained YOLO weights (YOLOv8).
- Configure detection thresholds (confidence, IoU).
  
- Detection
- Run YOLO inference on input images.
- Extract bounding boxes, class IDs, and confidence scores.
  
- Visualization
- Overlay bounding boxes and labels on original images.
- Save rectified objects for further analysis


📈 Results
- YOLO successfully detected multiple objects with high accuracy.
- Rectification standardized object dimensions, enabling consistent downstream analysis.
- Visualizations highlight bounding boxes and corrected object crops.


