# Plant-Leaf-Diseases-Detection-Using-CNN🌿

A project to detect plant leaf diseases using Convolutional Neural Networks (CNN). This system classifies leaf images into three categories: **Healthy**, **Rust-Infected**, and **Powdery Mildew-Infected**, aiming to assist farmers with early disease detection and improve crop yields.

---

## 🚀 Features
- **Image-Based Detection**: Upload an image of a leaf to detect its health status.
- **Disease Categories**:
  - Healthy
  - Rust-Infected
  - Powdery Mildew
- **User-Friendly Interface**: A simple and intuitive UI for uploading images and viewing results.
- **High Accuracy**: Achieved an accuracy range of **70%-99%** across all disease classifications.
- **Fast Processing**: Get real-time results for immediate action.

---

## 🧐 Problem Statement
Plant diseases lead to significant crop losses, affecting food security and economic stability. Current manual methods for disease detection are slow, error-prone, and inaccessible to many farmers. This project aims to provide an automated, efficient, and accurate system for detecting plant leaf diseases.

---

## 💡 Proposed Solution
The project uses a **Convolutional Neural Network (CNN)** to classify leaf images. By leveraging image preprocessing and deep learning techniques, it ensures accurate disease detection and actionable insights for farmers.

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Machine Learning**: TensorFlow/Keras for CNN model
- **Database**: For storing datasets
- **Deployment**: Local or cloud-based deployment

---

## 📁 Dataset
The dataset consists of leaf images categorized into three classes:
- Healthy
- Rust-Infected
- Powdery Mildew

Images were preprocessed (resized, normalized, and augmented) to enhance model performance.

---

## ⚙️ System Architecture
1. **Input**: User uploads a leaf image through the web interface.
2. **Processing**:
   - Preprocessing the image (resizing, normalizing, augmenting).
   - Feeding the processed image into the CNN model for classification.
3. **Output**: The system displays the disease classification result.
4. **User Interface**: A web interface for seamless interaction.

---

## 🖼️ Screenshots
- **Model Performance**: Graphs showing accuracy and loss trends during training.
- ![Graph](https://github.com/user-attachments/assets/30725078-18ad-4a7e-b2d5-e354bba790a8)

- **User Interface**:
- ![1](https://github.com/user-attachments/assets/71c27cb9-9a9c-406d-ac50-36dbc8eaed41)
- 
- -------------------

- ![2](https://github.com/user-attachments/assets/8e4d1fd8-82cb-4c93-a4bc-079a5760ed0c)




---

## 🚧 Challenges and Future Work
### Challenges:
- Limited datasets for certain diseases.
- Variations in leaf shapes and lighting conditions.

### Future Developments:
- Expanding the dataset to include more diseases.
- Integrating the solution into a **mobile application** for field use.
- Leveraging **transfer learning models** to enhance performance.
- Adding real-time detection via a live camera feed.

---

## 📊 Results
- **Accuracy**: 70%-99% for disease classification.
- **Precision and Recall**:
     -Healthy: Precision 95%, Recall 93%
     -Rust: Precision 92%, Recall 90%
     -Powdery Mildew: Precision 96%, Recall 94%

---

## 🤝 Contributors
  -Surya Pratap Verma: Model development, UI design, testing.
  -Shagun Chauhan: Data collection, documentation, testing.
