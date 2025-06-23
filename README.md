# 🧠 Deepfake Video Detector

> An AI-powered system to detect deepfake videos using facial feature extraction and deep learning models.

## 📌 Overview

This project aims to detect deepfake videos using face-based feature extraction techniques and classify them using deep learning models like ResNeXt-101. It leverages frame-level face extraction from video files and evaluates them to distinguish between real and fake content.

## 🔍 Features

- 🎥 Frame-level face extraction using MTCNN
- 🧑‍💻 Face classification using ResNeXt-101 pretrained on ImageNet
- 📊 Evaluation using metrics like accuracy, precision, recall, and F1-score
- 📦 Modular code structure
- 🚀 Future scope for real-time detection and deployment


## ⚙️ How It Works

1. **Extract frames from video**
2. **Detect and crop faces using HaarCasacde**
3. **Preprocess faces for the model**
4. **Run inference with ResNeXt-101**
5. **Output the prediction (Real or Fake)**

🔬 Dataset
FaceForensics++ (https://github.com/ondyari/FaceForensics)

💡 Future Work
Real-time detection via webcam/live streaming

Mobile-friendly model compression

GAN-specific fake classification

🙋‍♀️ Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.



