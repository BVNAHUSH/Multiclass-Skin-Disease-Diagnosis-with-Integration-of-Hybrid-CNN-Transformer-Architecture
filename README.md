**🧠Interpretable Deep Learning for Skin Disease Diagnosis
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
<img width="1170" height="780" alt="image" src="https://github.com/user-attachments/assets/9a70cbee-d090-40da-8f94-ef6516e0cf07" />


🔹 Multiclass classification of dermatological conditions

🔹 Focus on clinical interpretability and usability

**🗂 Dataset**

The model is trained on a curated dermatological dataset containing:

Melanoma

Eczema

Acne / Rosacea

Nail Fungus

Benign Tumors
<img width="1123" height="616" alt="image" src="https://github.com/user-attachments/assets/3ca71ba3-3033-4e21-81fd-f04aac3f9b7f" />


**📊 Preprocessing Steps:**

Image resizing → 224 × 224
Normalization
Data augmentation:
Rotation
Flipping
Zooming
Handling class imbalance

**🏗 Model Architecture**

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

<img width="1048" height="707" alt="image" src="https://github.com/user-attachments/assets/8a4901a6-1e24-4f33-a9b4-68d6be745796" />


**📈 Evaluation Metrics:**
Accuracy



Precision

Recall

F1-score
<img width="1102" height="355" alt="image" src="https://github.com/user-attachments/assets/d4b3e763-85e2-4c09-a135-0bfefea845f7" />


ROC-AUC
<img width="541" height="419" alt="image" src="https://github.com/user-attachments/assets/301df8d5-01a0-4fa3-b2db-d72dfa76bcb2" />

Confusion Matrix
<img width="507" height="400" alt="image" src="https://github.com/user-attachments/assets/da3bba34-00e0-489b-927d-906b4ca23bb8" />

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
<img width="802" height="360" alt="image" src="https://github.com/user-attachments/assets/5773214c-b28d-4bd2-8a5c-7cdaa5fa7388" />
<img width="800" height="368" alt="Screenshot 2025-12-02 022501" src="https://github.com/user-attachments/assets/4f0cad37-386c-4346-a144-c4ed31cb9c23" />
<img width="800" height="372" alt="Screenshot 2025-12-02 024615" src="https://github.com/user-attachments/assets/f28b7c13-bbda-4eb9-bd4a-6cb5f1967257" />

<img width="629" height="685" alt="Screenshot 2025-12-02 025415" src="https://github.com/user-attachments/assets/ff3bcb49-c0c2-4f4f-936f-778e6065fce6" />

 
**💡 Key Learnings**
Accuracy alone is not enough in healthcare AI

Interpretability is critical for adoption

Transformers outperform CNNs in capturing global patterns

Hybrid models are the future of medical imaging

**🌍 Real-World Impact**
Can assist doctors in diagnosis

Useful in rural / low-resource settings

Reduces dependency on specialists

Enables faster and more reliable decision-making

**📄 Research Paper**

**📌 Interpretable Deep Learning Model for Multiclass Skin Disease Diagnosis with Integration of Hybrid CNN–Transformer Architecture**

🔗 https://xplorestaging.ieee.org/document/11495657

**👥 Authors**

B V Nahush

Sushmitha H M

Istarth H V


Guide: Sivaramakrishnan S


**🔮 Future Work**

Improve model explainability with advanced XAI techniques

Deploy as a web/mobile application

Expand dataset diversity

Integrate real-time clinical validation

**⭐ If you found this useful**

Give a ⭐ to support the project!


Let’s discuss AI, research, or collaborations 🚀
