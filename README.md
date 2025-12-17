# 🚘 License Plate Detection & Recognition using YOLOv8

An end-to-end **Automatic License Plate Recognition (ALPR)** system using **YOLOv8** for license plate detection and **Tesseract OCR** for text recognition.  
The system is trained on a **Roboflow public license plate dataset** and performs inference on real-world video data.

---

## 📌 Project Highlights
- YOLOv8-based license plate detection
- Custom training using Roboflow dataset
- Video-based inference
- Automatic license plate cropping
- OCR using Tesseract
- Annotated output video with bounding boxes and text
- Training metrics visualization (loss, precision, recall, mAP)

---

## 🧠 System Workflow
1. Dataset download from Roboflow (YOLOv8 format)
2. Training YOLOv8 using pretrained weights
3. Detect license plates in each video frame
4. Crop detected plates
5. Preprocess images for OCR
6. Extract text using Tesseract
7. Overlay detection + text on video
8. Save final output video

---
