# Knight's Eye 👁️  
### Real-Time AI Surveillance System for Harassment Detection

> Hackathon Finalist Project — Sathakathon 2024

Knight’s Eye is an AI-powered real-time surveillance system designed to detect harassment, violence, and abuse-related activities from CCTV/live video streams using Deep Learning and Temporal Action Recognition.

Unlike traditional frame-by-frame detection systems, Knight’s Eye understands actions over time by analyzing continuous sequences of frames, enabling more accurate behavior recognition in real-world surveillance environments.

---

## 🚀 Highlights

- Real-time CCTV monitoring
- Harassment & abuse behavior detection
- Temporal action recognition using 16-frame clips
- Instant automated alert generation
- Timestamped evidence clip saving
- Near real-time inference performance
- Reduced need for continuous manual CCTV monitoring

---

## 🧠 System Workflow

```text
Live CCTV Feed
       ↓
Frame Extraction
       ↓
16-Frame Clip Generation
       ↓
Preprocessing using OpenCV
       ↓
Deep Learning Model Inference
       ↓
Behavior Classification
       ↓
Alert + Evidence Generation
```

---

## ⚙️ Tech Stack

| Technology | Usage |
|---|---|
| Python | Core development |
| PyTorch | Deep learning pipeline |
| OpenCV | Video processing |
| NumPy | Data handling |
| CNN-Based Temporal Model | Action recognition |
| YOLOv8 | Person/Object Detection |

---

## 📂 Project Structure

```bash
WOMENS_SAFTY_ML/
│
├── data/               # Input video clips / dataset
├── features/           # Extracted feature vectors
├── models/             # Trained models
├── results/            # Prediction outputs
├── src/                # Core scripts
├── utils/              # Helper functions
├── model.pth           # Saved trained model
├── yolov8n.pt          # YOLO model weights
└── Women's_safety_full.ipynb
```

---

## 🔍 Key Features

### ✅ Temporal Action Recognition
Instead of predicting from a single frame, the system analyzes motion patterns across 16 continuous frames for improved contextual understanding.

### ✅ Real-Time Monitoring
Processes surveillance streams at approximately **25–30 FPS** with optimized inference speed.

### ✅ Fast Alert System
Triggers automated alerts within nearly **1 second** after detecting suspicious activity.

### ✅ Evidence Generation
Automatically stores timestamped clips for future verification and incident review.

---

## 📊 Performance

| Metric | Value |
|---|---|
| Input FPS | 25–30 FPS |
| Inference Time | 120–180 ms per clip |
| Alert Delay | ~1 second |
| Processing Type | Near Real-Time |

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/knights-eye.git
cd knights-eye
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python main.py
```

---

## 🎯 Use Cases

- Smart CCTV Surveillance
- Public Safety Monitoring
- Women Safety Systems
- Automated Threat Detection
- Security Control Rooms

---

## 🏆 Achievement

Finalist at **Sathakathon Hackathon 2024** for developing an AI-based real-time safety surveillance solution.

---

## 🔮 Future Improvements

- Multi-camera support
- Cloud dashboard integration
- Mobile push notifications
- Edge AI deployment
- Activity heatmap analytics

---

## 👨‍💻 Author

Developed as a hackathon and research project focused on intelligent real-time surveillance systems using AI and Computer Vision.
