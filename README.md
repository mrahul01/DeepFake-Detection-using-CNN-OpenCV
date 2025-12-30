# DeepFake-Detection-using-CNN-OpenCV
Deepfake detection system using computer vision feature extraction and Siamese neural networks to classify real and fake face images.



# Deepfake Detection Using Computer Vision and Siamese Neural Networks

This project focuses on detecting deepfake images by combining classical computer vision techniques with deep learning. The system extracts robust visual and frequency-domain features from face images and learns discriminative embeddings using a Siamese Neural Network trained with contrastive loss.

## 🔍 Key Features
- Gabor filter-based preprocessing to enhance facial artifacts
- Feature extraction using color statistics, edge density, histogram analysis, and DCT energy
- Optional fuzzy C-means clustering for additional intensity-based features
- Siamese Neural Network implemented in PyTorch for pairwise learning
- Contrastive loss to separate real and fake face embeddings in feature space
- Anchor-based evaluation for accurate real vs fake classification

## 🛠 Technologies Used
- Python, OpenCV, NumPy
- PyTorch (Siamese Network & Training)
- Scikit-learn (data handling)
- Google Colab / Linux environment

## 📊 Dataset
The model is trained and evaluated on a publicly available deepfake image dataset containing real and fake facial images.

## 🚀 Future Scope
- Extend the system to detect deepfake videos using temporal and frame-level consistency analysis
- Integrate CNN-based feature extractors for improved accuracy
- Deploy the model as a web application or REST API

## 📌 Use Cases
- Digital media forensics
- Misinformation and deepfake detection
- Research and educational demonstrations
