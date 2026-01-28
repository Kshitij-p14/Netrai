# NETRAI - Real-time Road Accident Detection System

![NETRAI Banner](https://img.shields.io/badge/Status-LIVE-brightgreen?style=for-the-badge) ![F1 Score](https://img.shields.io/badge/F1--Score-83.3%25-blue?style=for-the-badge) ![Python](https://img.shields.io/badge/Python-3.7+-yellow?style=for-the-badge)

##  Demo Video

https://github.com/Kshitij-p14/NETRAI/assets/117811916/netrai-demo.mp4

> **Watch the demo above to see NETRAI detecting accidents in real-time!**

[ Watch full demo on YouTube](https://www.youtube.com/watch?v=RYQQ_z88AnQ)

---

##  Overview

NETRAI is a cutting-edge real-time road accident detection system that leverages advanced computer vision and artificial intelligence to analyze CCTV footage and automatically detect vehicular accidents as they occur. Using YOLOv12 for object detection and Gemini 2 Flash for intelligent analysis, NETRAI provides instant notifications and detailed incident reports.

###  Key Achievements
- **83.3% F1-Score** in accident detection
- **Real-time processing** of CCTV footage
- **Instant notifications** to emergency services
- **Firebase cloud integration** for scalability

##  Features

-  **Advanced Object Detection** - YOLO11/YOLOv12-based accident detection
-  **Real-time CCTV Analysis** - Continuous monitoring and instant detection
-  **AI-Powered Analysis** - Gemini 2 Flash integration for intelligent incident assessment
-  **Instant Alerts** - Immediate notifications to emergency services
-  **Automated Storage** - Saves accident frames and descriptions automatically
-  **Cloud Backend** - Firebase integration for scalable deployment
-  **Detailed Reports** - Comprehensive incident documentation

##  Project Structure

`
Netrai/
 app2.py                 # Main application
 main.py                 # Core detection logic
 app.py                  # Alternative interface
 training/
    train-yolo11-object-detection-on-custom-dataset.ipynb
 models/
    best(5).pt         # Trained model weights
    best(4).pt
 requirements.txt        # Python dependencies
 netrai-demo.mp4        # Demo video
 README.md
`

##  Technology Stack

- **Computer Vision**: YOLOv11/YOLOv12
- **AI Analysis**: Google Gemini 2 Flash
- **Backend**: Firebase
- **Processing**: OpenCV, Python
- **Deep Learning**: PyTorch
- **Cloud**: Firebase Realtime Database

##  Prerequisites

- Python 3.7 or higher
- GPU recommended for real-time processing
- Firebase account (for cloud features)
- Google Gemini API key

##  Installation

### 1. Clone the Repository

`ash
git clone https://github.com/Kshitij-p14/NETRAI.git
cd NETRAI
`

### 2. Install Dependencies

`ash
pip install -r requirements.txt
`

### 3. Set Up Environment Variables

Create a .env file:
`ash
GOOGLE_API_KEY=your_gemini_api_key
FIREBASE_CONFIG=your_firebase_config
`

### 4. Run the Application

`ash
python main.py
`

### 5. Process Video

When prompted, input the path of the video you want to process for accident detection.

##  How It Works

1. **Video Input** - CCTV footage is fed into the system
2. **Object Detection** - YOLOv12 identifies vehicles and potential accidents
3. **AI Analysis** - Gemini 2 Flash analyzes detected incidents
4. **Alert Generation** - System triggers instant notifications
5. **Data Storage** - Frames and descriptions stored in Firebase
6. **Report Generation** - Detailed incident reports created automatically

##  Performance Metrics

| Metric | Value |
|--------|-------|
| F1-Score | 83.3% |
| Processing Speed | Real-time |
| Detection Accuracy | High |
| False Positive Rate | Low |

##  Use Cases

- **Smart Cities**: Automated traffic monitoring and incident response
- **Highway Management**: Real-time accident detection on major roads
- **Emergency Services**: Faster response times through instant alerts
- **Traffic Analysis**: Data-driven insights for road safety improvements
- **Insurance**: Automated incident documentation

##  Future Enhancements

- [ ] Multi-camera support
- [ ] Mobile app for alerts
- [ ] Advanced analytics dashboard
- [ ] Integration with emergency dispatch systems
- [ ] Predictive accident prevention
- [ ] Weather and visibility adjustment

##  Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

##  License

This project is for educational and demonstration purposes.

##  Author

**Kshitij Panchal**
- GitHub: [@Kshitij-p14](https://github.com/Kshitij-p14)
- LinkedIn: [Kshitij Panchal](https://www.linkedin.com/in/kshitij-panchal-5707b92a5/)
- Portfolio: [View Projects](https://kshitij-p14.github.io/portfolio)

##  Contact

For questions, collaboration, or demo requests, please reach out through:
- Email: panchalkshitij1@gmail.com
- LinkedIn: [Connect with me](https://www.linkedin.com/in/kshitij-panchal-5707b92a5/)

---

**NETRAI** - Saving lives through intelligent accident detection 
