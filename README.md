# Deepfake-and-Antispoofing-Using-Mobilenet-and-Resnext

```markdown
# 🔐 SecureVision

**SecureVision** is an integrated anti-spoofing and deepfake detection system designed to enhance biometric authentication security. This project uses a lightweight MobileNet model for spoof detection and a powerful ResNeXt + LSTM architecture for deepfake identification, ensuring robust and efficient protection against facial spoofing and video manipulation threats.

## 📌 Features

- 🛡️ Real-time **Anti-Spoofing Detection** using MobileNet
- 🎭 **Deepfake Detection** with ResNeXt backbone and LSTM for temporal sequence modeling
- 🌐 Simple and interactive **Flask-based Web Application**
- 🔍 High accuracy on benchmark datasets
- 💡 Modular design for easy experimentation and deployment

## 📂 Project Structure

```
SecureVision/
│
├── anti_spoofing/
│   ├── mobilenet_model.py
│   ├── train_antispoof.py
│   └── ...
├── deepfake_detection/
│   ├── resnext_lstm.py
│   ├── train_deepfake.py
│   └── ...
├── web_app/
│   ├── app.py
│   ├── templates/
│   ├── static/
│   └── ...
├── datasets/
│   ├── [training and testing data]
├── utils/
│   └── helper_functions.py
├── models/
│   └── [pre-trained weights]
├── requirements.txt
└── README.md
```

## 🧪 Tech Stack

- **Python 3.8+**
- **TensorFlow / Keras** – for anti-spoofing model
- **PyTorch** – for deepfake detection model
- **OpenCV** – for image and video processing
- **Flask** – for backend API and web interface
- **HTML/CSS/JavaScript** – frontend UI

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Sedhupxthi/SecureVision.git
cd SecureVision
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Web Application

```bash
python web_app/app.py
```

Open your browser and navigate to:  
👉 `http://127.0.0.1:5000`

## 🧠 Model Training (Optional)

You can retrain the models if needed using the following scripts:

#### Train Anti-Spoofing Model:

```bash
python anti_spoofing/train_antispoof.py
```

#### Train Deepfake Detection Model:

```bash
python deepfake_detection/train_deepfake.py
```

> 💾 Pre-trained models can be added to the `models/` directory for direct testing.

## 📈 Results

| Task               | Model           | Accuracy |
|--------------------|------------------|----------|
| Anti-Spoofing      | MobileNet        | 97.5%    |
| Deepfake Detection | ResNeXt + LSTM   | 92.3%    |

## 🎥 Demo

<!-- Replace with actual video link if available -->
[![Watch Demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

## 📌 Future Enhancements

- ✅ Live camera integration
- 📱 Mobile version using TensorFlow Lite
- 🧠 Model optimization for edge deployment
- 🧪 More datasets for robust evaluation

## 👨‍💻 Author

**Sedhupathi Rajendran**  
Final Year BTech CSE (Data Science), VIT Vellore  
📧 sedhupathirajendran@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/sedhupathi/)  
🐙 [GitHub](https://github.com/Sedhupxthi)

## 📄 License

This project is licensed under the [MIT License](LICENSE).
```
