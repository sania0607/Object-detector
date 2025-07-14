# 🧠 Real-Time Object Detection using YOLOv8 + OpenCV

Detect objects in real-time using YOLOv8 and your webcam!

---

## 🚀 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/saniarajput06/yolo-object-detector.git
cd yolo-object-detector
```

### 2. Install Dependencies

**Option A: Using `requirements.txt`**

```bash
pip install -r requirements.txt
```

**Option B: Manually Install Each**

```bash
pip install opencv-python
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install ultralytics
```

### 3. Run the App

```bash
python main.py
```

A webcam window will open.  
Objects will be detected in real-time with bounding boxes and labels.  
Press `q` to quit the app.

---

## 🗂️ Project Structure

```
opencv/
├── main.py
├── requirements.txt
├── README.md
└── yolov8n.pt         # YOLOv8 model file (downloaded automatically if missing)
```

---

## 🧠 How It Works

- Loads the lightweight YOLOv8n model (`yolov8n.pt`)
- Captures webcam frames using OpenCV
- Detects & classifies objects using YOLOv8
- Draws bounding boxes with:
  - Object label (e.g., "person")
  - Confidence score (e.g., 0.91)
- Real-time visual feedback

---

## 💡 Sample Output

```
Detected: person 0.91
Detected: cell phone 0.85
