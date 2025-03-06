# Comparison of our and Author Results



| Model       | Precision (B) | Recall (B) | mAP50 (B) | 
|------------|-------------|-----------|-----------|
| YOLOv11 (Author)    | 66.4      | 64.8    | 57.2    |
| YOLO v11 (Ours 1) | 0.6658945349052345      | 0.6051868935807482       | 0.6238935040139992       |
| YOLO v11 (Ours 2) | 0.79763732941179      | 0.5216777395832599       | 0.6434454997283249       |


Parameters For our runs

| Parameter          | Ours-2  | Ours-1 | 
|-------------------|----------------------|--------------|
| **Optimizer**    | SGD                  | Auto (selected AdamW) | 
| **Learning Rate** | 0.01                 | Auto-selected (AdamW used 0.001667) | 
| **IoU Threshold** | 0.5                  | Default (Not set, assumed 0.7) | 
| **Input Image Size** | 640 × 640           | Default (Not set, assumed 640 × 640) | 
