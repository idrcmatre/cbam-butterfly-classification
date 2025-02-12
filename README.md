# 🦋 Butterfly Classification with CBAM + EfficientNetB0

This deep learning project classifies butterfly images into species, genus, subfamily, and family using a multi-output CNN model with **EfficientNetB0** and **CBAM (Convolutional Block Attention Module)**.

## 📌 Project Highlights

- Multi-task learning for hierarchical classification
- CBAM added to EfficientNetB0 for spatial & channel attention
- TFRecord input pipeline + real-world data augmentation
- Class imbalance handled via calculated weights
- Visualized confusion matrix & accuracy over epochs

## 🧠 Final Results

- **Top-1 Accuracy**: 73.37%  
- **Top-5 Accuracy**: 95.38%  
- Dataset: 200 Butterfly Species

## 📂 Structure

├── notebooks/ ├── data/ ├── .gitignore ├── README.md ├── LICENSE

## 🧰 Tech Stack

Python, TensorFlow, Keras, CBAM, EfficientNet, Matplotlib, TFRecords

## 🪪 License

This project is licensed under the MIT License.
