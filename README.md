# YOLOv8 Real-Time Object Tracking


## 📌 Project Description
This project implements real-time object tracking using **YOLOv8** and **OpenCV**. The model detects and tracks objects in a live video feed using a webcam.

## 🚀 Features
- Real-time object detection & tracking
- Uses **YOLOv8** for high accuracy
- Displays class names and confidence scores
- Assigns unique colors to different object classes
- Runs efficiently with OpenCV

## 🛠️ Setup and Installation
### **1️⃣ Install Dependencies**
Ensure you have Python installed (>=3.7), then install the required libraries:

```bash
pip install ultralytics opencv-python numpy
```

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/yourusername/yolo-object-tracking.git
cd yolo-object-tracking
```

### **3️⃣ Import YOLOv8 Model**
Importing the pre-trained YOLOv8 model:
```bash
from ultralytics import YOLO
```

## 🎯 Usage
### **Run Object Tracking**
```bash
python yolo_tracking.py
```

### **Run in Jupyter Notebook**
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open `yolo_tracking.ipynb` and run the cells step by step.


## 📌 Customization
- Modify `yolov8s.pt` to use a different model (e.g., `yolov8m.pt`, `yolov8l.pt`).
- Adjust confidence threshold (`box.conf[0] > 0.4`) for sensitivity tuning.
- Change colors in the `getColours()` function.

## 🛠️ Troubleshooting
- **Webcam not opening?** Ensure it's not being used by another program.
- **Performance issues?** Reduce image resolution or use a smaller YOLO model.
- **Module not found?** Run `pip install -r requirements.txt` to install dependencies.



