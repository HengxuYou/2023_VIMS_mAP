# 2023_VIMS_mAP
The github repo for 2023 VIMS datathon

## Model Selection
YOLOv8 by [ultralytics](https://github.com/ultralytics/ultralytics/tree/main)

## Dataset Selection
[Base](https://repositorio.ulima.edu.pe/handle/20.500.12724/13359) by ["Dataset on object identification training in a construction site"](https://www.sciencedirect.com/science/article/pii/S2352340922002530?ref=pdf_download&fr=RR-2&rr=7da30b28fc8b0a32)<br/>
Augmentation: Flipping, cropping, noising, bounding-box clipping, bounding box rotation

## Environmen Requirements
python==3,9<br/>
cv2==4.7.0<br/>
torch==1.11.0<br/>
ultralytics==8.0.119
