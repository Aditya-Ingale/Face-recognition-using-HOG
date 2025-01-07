# Robust Face Detection and Identification

This project focuses on developing a robust face recognition system using HOG-based feature extraction and machine learning classifiers. Designed with educational website integration in mind, this system offers features such as real-time face detection, feature extraction, and efficient classification.

---

## **Project Workflow**

1. **Data Collection**: Images from three subjects were collected using a webcam (300 images per subject) under controlled lighting conditions.
2. **Preprocessing**:
   - Image resizing to a standard dimension (256x256 pixels).
   - Grayscale conversion to simplify image analysis.
   - Histogram equalization for enhanced contrast.
   - Median blur to reduce noise while retaining image details.
3. **Face Detection**: Used Haar Cascade Classifier for efficient and real-time detection.
4. **Feature Extraction**: Applied the Histogram of Oriented Gradients (HOG) technique, extracting ~15,000 features per image.
5. **Dimensionality Reduction**: Leveraged Principal Component Analysis (PCA) to optimize computational efficiency.
6. **Classification**: Experimented with several machine learning classifiers:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Random Forest (RF)
   - Support Vector Machine (SVM)

---

## **Results**

Among all classifiers tested, Logistic Regression delivered the best accuracy at **99.54%**. This showcases the potential for robust and efficient face recognition when combining preprocessing, feature extraction, and machine learning.

| Classifier          | Accuracy (%) |
|---------------------|--------------|
| Logistic Regression | 99.54        |
| KNN                 | 97.12        |
| Random Forest       | 99.62        |
| SVM                 | 98.85        |

### Comparison Graph
![Accuracy Bar Graph](#) <!-- Add the path to your image file here -->

### Sample Output
| Image Recognized     | Image Not Recognized     |
|-----------------------|--------------------------|
| ![Recognized](#)      | ![Not Recognized](#)     |

---

## 🌟 **Future Scope**

- **Deep Learning Integration**: Explore CNN-based architectures for feature extraction.
- **Real-Time Processing**: Enhance performance for instantaneous face recognition.
- **Scalability**: Adapt the system to handle larger datasets and diverse environments.
- **Applications**: Attendance management and personalized user experiences.

---

## 📄 **Published Paper**

You can read the full research paper here: [Robust Face Detection and Identification Using HOG-based Features and Machine Learning](https://doi.org/10.1109/INCOFT60753.2023.10425077). <!-- Replace `#` with the actual link to your published paper -->

