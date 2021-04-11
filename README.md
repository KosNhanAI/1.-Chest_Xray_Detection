# Chest_Xray_Detection
This project used pretrained model RetinaNet of fizyr for thoracic lung diseases detection
- Link dataset: https://www.kaggle.com/c/vinbigdata-chest-xray-abnormalities-detection
- Link: https://github.com/fizyr/keras-retinanet

- This project is described is more detail in project_analysis folder
### 1. Non Maximum Suppression (NMS), Soft Non Maximum Suppression (Soft - NMS) and Weighted Boxes fusion (WBF)
||      Number of Boxes      | 
|----------|:-------------:|
| Original Boxes | 36,096|
| NMS| 23,940|
| Soft - NMS | 32,273 |
|WBF | 23,955|

> Base on the result and algorithm of these techniques. I selected WBF > 

**Before and after apply WBF**
[img_1](image_in_markdown/Image_before_after.png)
### 2. 
