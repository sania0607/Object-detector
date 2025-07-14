# 🧠 Real-Time Object Detection using YOLOv8 + OpenCV

# Detect everyday objects (like people, bottles, laptops, chairs, etc.)
# in real-time using your webcam, powered by Ultralytics YOLOv8 and OpenCV.

# ------------------------
# 📦 INSTALLATION
# ------------------------

# Step 1: Clone this repository
git clone https://github.com/saniarajput06/yolo-object-detector.git
cd yolo-object-detector

# Step 2: Install dependencies (choose ONE of the following)

# ✅ Option A: Use requirements.txt
pip install -r requirements.txt

# ✅ Option B: Manually install each
pip install opencv-python
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install ultralytics

# ------------------------
# ▶️ RUN THE APP
# ------------------------

python main.py

# This will:
# - Open your webcam
# - Detect objects like "person", "cup", "cell phone", etc.
# - Draw bounding boxes with labels and confidence scores
# - Press 'q' to exit the app

# ------------------------
# 🧠 HOW IT WORKS
# ------------------------

# - Loads YOLOv8 Nano model (yolov8n.pt)
# - Captures frames using OpenCV from your webcam
# - YOLO detects & classifies objects in the frame
# - You get:
#     - Object label (e.g. 'person', 'cup')
#     - Confidence score (e.g. 0.91)
#     - Bounding box around object
# - The detection runs in real time and shows everything in a window

# ------------------------
# 💡 SAMPLE OUTPUT (in terminal)
# ------------------------

# Detected: person 0.91
# Detected: cell phone 0.85
# Detected: chair 0.77

# ------------------------
# 🛠️ CUSTOMIZATION IDEAS
# ------------------------

# - 🎯 Detect only specific object types (e.g., just people)
# - 🎥 Run it on saved videos or image files
# - 🧮 Count how many people are in the frame
# - 💾 Save screenshots of detections
# - 🌐 Deploy it on a web app using Streamlit or Flask

# ------------------------
# 📁 FOLDER STRUCTURE
# ------------------------

# .
# ├── main.py
# ├── README.md
# └── requirements.txt

# ------------------------
# 🧑‍💻 AUTHOR
# ------------------------

# Made with 💙 by Sania Rajput
# LinkedIn: https://www.linkedin.com/in/saniarajput06/




