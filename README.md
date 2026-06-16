# 🚨 Traffic Accident Detection System

An AI-powered web application that detects road accidents from traffic images using YOLOv8 and Computer Vision techniques.

## 🔄 System Workflow

```mermaid
flowchart TD
    A[Upload Traffic Image] --> B[Image Preprocessing]
    B --> C[YOLOv8 Model]
    C --> D[Feature Extraction]
    D --> E{Accident Detected?}

    E -->|Yes| F[Display Accident Detected]
    E -->|No| G[Display No Accident Detected]

    F --> H[Show Annotated Image]
    G --> H
```

## 🛠️ Tech Stack

- Python
- Flask
- YOLOv8
- OpenCV
- HTML
- CSS

## ✨ Features

- AI-based accident detection
- Traffic image analysis
- Real-time prediction
- User-friendly web interface
- Annotated accident detection results

## 🚀 Project Flow

```mermaid
flowchart LR
    Dataset --> Training
    Training --> YOLOv8_Model
    YOLOv8_Model --> Flask_App
    Flask_App --> User_Interface
    User_Interface --> Prediction_Result
```

## ▶️ Run Project

```bash
python app.py
```

## 👨‍💻 Authors

- Pavithra Prem
- Neelima B
- Renjima Rajeev
- Vinitha PJ

