# Number Plate Detection using YOLO

This project implements number plate detection using the YOLO (You Only Look Once) object detection algorithm from the Ultralytics library. It can be used to identify and localize vehicle number plates in images or videos.

## 📌 Features

- Real-time number plate detection
- Powered by Ultralytics YOLOv8
- Easy to set up and run on any system with Python
- Can process images and videos

## 🔧 Installation

First, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/numberplate-detection.git
cd numberplate-detection
pip install -r requirements.txt
```

Alternatively, if you're running the notebook directly:

```bash
pip install ultralytics --upgrade
```

## 🚀 Usage

Run the Jupyter Notebook:

```bash
jupyter notebook numberplateprediction.ipynb
```

Or use the Python script (if available):

```bash
python detect_numberplate.py --source path/to/image_or_video
```

Make sure to place your images/videos in the appropriate folder or update the path accordingly.

## 🧠 Model Details

- **Model Used**: YOLOv8 from [Ultralytics](https://github.com/ultralytics/ultralytics)
- **Pretrained Weights**: Optionally use pretrained weights like `yolov8n.pt`, `yolov8s.pt`, etc., or train your own model on a custom dataset.
- Supports real-time detection on both CPU and GPU.

## 📂 Output

- The detected number plates are displayed with bounding boxes.
- Results are saved in the `runs/detect` directory by default (if using YOLO's `.predict()` method).
- Sample output format:

```
Input image/video → Detection → Bounding boxes around number plates → Saved result
```

## 📁 File Structure

```
numberplate-detection/
│
├── numberplateprediction.ipynb  # Main notebook
├── detect_numberplate.py        # (Optional) Python script for detection
├── requirements.txt             # Python dependencies
├── runs/                        # YOLO output folder
└── README.md                    # Project documentation
```

---

Created using YOLO and Python by HARISEKHAR.
