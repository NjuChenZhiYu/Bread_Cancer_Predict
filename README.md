# Breast Cancer Prediction

Breast cancer is a malignant growth that develops in the cells of the breast tissue. It typically originates in the lining cells (epithelium) of the ducts (accounting for approximately 85%) or lobules (about 15%) within the glandular tissue of the breast.

In its early stage, the cancer is often confined to the duct or lobule (known as "in situ"), rarely causing noticeable symptoms and having minimal potential for metastasis (spread). Most breast cancers can be diagnosed quite accurately through microscopic examination of tissue samples obtained via biopsy. Some special cases may require additional lab tests for precise diagnosis.

This project focuses on developing machine learning models for breast cancer prediction based on various features extracted from medical data. Our goal is to assist in early detection and diagnosis, thereby improving treatment outcomes.

### What you will find in this repository:
- Data processing and feature engineering
- Machine learning models (e.g., Random Forest, SVM, Deep Learning)
- Model evaluation and performance metrics
- Tools for visualizing feature importance and prediction results

### Why it matters:
Early diagnosis of breast cancer can significantly increase survival rates. By leveraging advanced data analysis and AI techniques, we aim to provide a reliable tool for clinicians to support decision-making and improve patient care.

---


### Model Performance Summary

The performance of various models on the evaluation dataset is summarized below:

- **Logistic Regression (AUC):** 0.9737  
- **K-Nearest Neighbors (KNN) (AUC):** 0.9649  
- **Random Forest (AUC):** 0.9649  
- **Support Vector Machine (SVM) (AUC):** 0.9737  
- **Deep Neural Network (AUC):** **0.9977**  

Among these, the Deep Neural Network achieved the highest AUC of **0.9977**, demonstrating superior predictive performance in this task.

These results indicate that deep learning models are highly effective for this problem, significantly outperforming traditional machine learning algorithms.


Feel free to explore the code, datasets, and detailed methodology inside this repository to learn more about breast cancer prediction and how AI can aid medical diagnosis.
