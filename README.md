# Detection of Diabetic Retinopathy Using Deep Learning

## 📋 Overview

This research focuses on the early detection of Diabetic Retinopathy (DR) using deep learning models. DR is a severe complication of diabetes that can lead to vision loss if not diagnosed in time. The study leverages convolutional neural networks (CNNs) to automate the detection process, enhancing diagnostic accuracy and reducing manual efforts.

## 🧪 Key Features

- **Automated DR Detection:** Utilizes fundus images to identify and classify DR.
- **Multiclass & Binary Classification:** Classifies images into multiple DR stages and differentiates between DR and non-DR conditions.
- **CNN Models:** Implements ResNet-18, GoogLeNet, VGGNet-19, and AlexNet for feature extraction and classification.

## 📊 Datasets

- **APTOS 2019 Dataset:** Comprises 3662 high-quality fundus images.
- **Classification Labels:**
  - **Multiclass:** No DR, Mild DR, Moderate DR, Severe DR, Proliferative DR
  - **Binary:** DR and Non-DR

## ⚙️ Methodology

1. **Data Preprocessing:** Image augmentation, resizing, and normalization.
2. **Model Training:**
   - ResNet-18 and GoogLeNet for both multiclass and binary classification.
   - Models trained for 100 epochs with a batch size of 32.
3. **Performance Evaluation:** Accuracy, precision, recall, F1-score, AUC, sensitivity, specificity, and kappa coefficient.

## 🚀 Results

- **ResNet-18:**
  - Multiclass Classification Accuracy: **87%**
  - Binary Classification Accuracy: **98%**
- **GoogLeNet:**
  - Multiclass Classification Accuracy: **73%**
  - Binary Classification Accuracy: **94%**

ResNet-18 outperformed other models in both binary and multiclass classification tasks.

## 💻 Implementation

- **Tools & Technologies:**
  - Python
  - TensorFlow, Keras, NumPy, Pandas
  - Google Colab (GPU: Tesla K80)

## 📈 Future Scope

- Implementing advanced models like DenseNet and InceptionNet.
- Exploring Explainable AI (XAI) for interpretability.
- Expanding to other retinal diseases such as glaucoma and macular degeneration.

## 👩‍💻 Authors

- **Pooja Bidwai**, **Shilpa Gite**, **Kenil Patwa**, **Kushagra Maheshwari**, **Tanmay Singh Bais**, **Kavan Batavia**  
Symbiosis Institute of Technology, Pune, India

## 📜 Acknowledgments

The authors acknowledge the support of Symbiosis Institute of Technology, Pune, for providing computational resources.

## 🔗 References

[Refer to the original research paper for detailed references and literature review.](https://ieeexplore.ieee.org/abstract/document/10126384)

