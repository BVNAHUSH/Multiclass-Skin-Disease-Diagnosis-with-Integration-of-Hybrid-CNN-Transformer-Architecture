🧠** Interpretable Deep Learning for Skin Disease Diagnosis
Hybrid CNN–Transformer with Explainable AI (XAI)**
📌 Overview

Skin diseases are among the most common health issues globally, especially in regions with limited access to dermatologists. Early and accurate diagnosis is critical—but traditional diagnosis depends heavily on expert interpretation.

This project focuses on building an interpretable deep learning framework for multiclass skin disease classification, combining:

Convolutional Neural Networks (CNNs)
Vision Transformers (ViT)
Explainable AI (XAI) techniques

The goal is not just high accuracy—but trustworthy and explainable predictions for real-world healthcare applications.

**🚀 Key Contributions**

🔹 Hybrid deep learning approach combining CNN + Transformer architectures

🔹 Comparative analysis of:
ResNet50V2
DenseNet121
EfficientNetB3
Vision Transformer (ViT)

🔹 Integration of Explainable AI (XAI):
Grad-CAM
Integrated Gradients

🔹 Multiclass classification of dermatological conditions

🔹 Focus on clinical interpretability and usability

**🗂 Dataset**

The model is trained on a curated dermatological dataset containing:

Melanoma
Eczema
Acne / Rosacea
Nail Fungus
Benign Tumors
📊 Preprocessing Steps:
Image resizing → 224 × 224
Normalization
Data augmentation:
Rotation
Flipping
Zooming
Handling class imbalance
🏗 Model Architecture
🔹 CNN Models
ResNet50V2 → strong baseline with residual learning
DenseNet121 → efficient feature reuse
EfficientNetB3 → optimized scaling
🔹 Transformer Model
Vision Transformer (ViT)
Captures global context
Learns long-range dependencies
🔹 Hybrid Insight

CNNs capture local texture patterns
Transformers capture global relationships

👉 Combining both improves performance and generalization

**📊 Results**
Model	Accuracy	Key Insight
ResNet50V2	80%	Strong baseline
DenseNet121	78%	Stable performance
Vision Transformer (ViT)	89%	Best performance

**📈 Evaluation Metrics:**
Accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion Matrix

**🔍 Explainable AI (XAI)**

One of the biggest challenges in healthcare AI is lack of transparency.

This project integrates:

🔹 Grad-CAM
Highlights important regions in the image
Shows where the model is looking

🔹 Integrated Gradients
Assigns importance to input features
Explains why the prediction was made

👉 These techniques help bridge the gap between AI predictions and clinical trust

**🧪 Training Details**
Optimizer: Adam
Loss Function: Cross-Entropy
Transfer Learning: ImageNet pre-trained weights
Regularization: Early stopping
Input Size: 224 × 224
📷 Sample Outputs (Add your images here)
/images
  ├── gradcam_example.png
  ├── confusion_matrix.png
  ├── roc_curve.png
💡 Key Learnings
Accuracy alone is not enough in healthcare AI
Interpretability is critical for adoption
Transformers outperform CNNs in capturing global patterns
Hybrid models are the future of medical imaging
🌍 Real-World Impact
Can assist doctors in diagnosis
Useful in rural / low-resource settings
Reduces dependency on specialists
Enables faster and more reliable decision-making
📄 Research Paper

📌 Interpretable Deep Learning Model for Multiclass Skin Disease Diagnosis with Integration of Hybrid CNN–Transformer Architecture

🔗 https://xplorestaging.ieee.org/document/11495657

👥 Authors
Nahush B V
Sushmitha H M
Istarth H V

Guide: Sivaramakrishnan S

🔮 Future Work
Improve model explainability with advanced XAI techniques
Deploy as a web/mobile application
Expand dataset diversity
Integrate real-time clinical validation
⭐ If you found this useful

Give a ⭐ to support the project!

🔗 Connect

Let’s discuss AI, research, or collaborations 🚀
