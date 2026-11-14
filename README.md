The following repository is mainly for doing personal experiments with compute vision learning and understanding, mainly focused on the use application of Ultralytics Models. (Please visit the main page for detailed documentation and models: https://docs.ultralytics.com/)

---

IMPORTANT: The main purpose is only personal learning and training in the field of computer vision, not a commercial or industry real purposes.

----

The repository is divided into notebook cases:
- 01_yolo_vs_yoloe.ipynb : Comparison between YOLO and YOLOE for understanding in object detection and segmentation mainly.
- 02_yolo_video_cars.ipynb : Use of YOLO models for video processing like tracking and many other features from Ultralytics solutions module
- 03_yolo_tracking_theory.ipynb : Tracking theory and application with Ultralytics models. Main focus on the use of ByteTrack and BoT-SORT for tracking cases.
- 04_yolo_custom_layers.ipynb : Understanding from zero pytorch formats and then how to add pytorch NN layers in both cases at the end and in the middle to see how performance improves in the overall classifier case.
- 05_yolo_export_formats.ipynb : Learn and understand main format file for export the model trained like .pt (pytorch), .torchscript, .onnx (open neural network exchange)
- 06_yolo_compliance_security.ipynb :  understand some main compliance features and security understanding when using Ultralytics models

Some output examples to be found in the notebooks:

1)  Object detection and segmentation using YOLO vs YOLOE
<img width="719" height="525" alt="image" src="https://github.com/user-attachments/assets/21859423-5011-4342-81a2-304ac0ae67b2" />
<img width="789" height="525" alt="image" src="https://github.com/user-attachments/assets/08471978-c88e-41f7-b6e7-91d63aaae319" />

2) Object detection and segmentation in video
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/f9991424-25e3-4916-8d14-e1f2a03da678" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/e6b82cb0-9aec-4403-acac-f3a9959bd13e" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/1352aad6-7862-49ac-b134-1aa62c0cf9c9" />

3) Tracking methods in video, mainly ByteTrack and BoT-SORT
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/0914bf0e-60c9-402f-8509-0b21de0ed8fd" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/216be849-20e8-4fff-918e-0c0012cb84b6" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/ad6e8311-48ad-4908-964f-15ab8b8a4bc3" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/bd1b1f68-a2b3-46a9-bcdb-b52261bf0d36" />


4) Multiple Yolo module "solutions" for tracking, counting, monitoring, blur, heatmap and more
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/77a69b32-98e1-470d-951b-2d9a3f40ce72" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/9e439bd9-8cc6-47b7-8cb1-d474c8d86fda" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/6e8ab624-a86e-4561-9fee-84aa038a4cdc" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/6488662a-1a89-4c95-b12c-1dd12f923b2e" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/eae4e2cb-e89d-48b7-9ae5-ce57b165a55c" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/2a10bf9a-30f6-4cc7-ae28-f47c77897182" />
<img width="795" height="477" alt="image" src="https://github.com/user-attachments/assets/35b7030a-392a-4b80-bef2-1ac7b66f121b" />

5) Adding layers into a YOLO model to train specific cases. Example of a classifier

Case 1: Add layer at the end only, few ones:
<img width="691" height="315" alt="image" src="https://github.com/user-attachments/assets/796391bf-dfeb-4320-aa99-bca3bc08f614" />

Case 2: Add intermediate layers in the main backbone model:
<img width="691" height="315" alt="image" src="https://github.com/user-attachments/assets/dfc6177f-0c8b-46af-b50b-f7d6912d35a5" />
