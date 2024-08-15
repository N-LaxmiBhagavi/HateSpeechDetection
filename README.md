# HateSpeechDetection
![Screenshot 2024-08-15 183030](https://github.com/user-attachments/assets/d50dba3c-94ea-4e60-843a-1e3912b5e815)

---
This project focuses on detecting hate speech in text using a machine learning model. The notebook provides a step-by-step approach to building and evaluating a hate speech detection model using various natural language processing (NLP) techniques.
### Steps to perform Hate-Speech-Detection:
- __Data Cleaning:__ Run the cells related to text cleaning to prepare your data for feature extraction.
- __Feature Extraction:__ Use Count Vectorizer to convert text into numerical features.
- __Model Training:__ Train the decision tree model using the provided dataset.
- __Model Evaluation:__ Evaluate the model performance on the test set.
- __Prediction:__ Use the trained model to predict the category of new text inputs.

### Results
The model can classify text into three categories:
- __Hate Speech:__ Text that contains hate speech.
- __Offensive Language:__ Text that contains offensive language but is not classified as hate speech.
- __Neither:__ Text that is neither hate speech nor offensive.

### Limitations
- The model's accuracy is highly dependent on the quality and diversity of the training data.
- The decision tree model might not generalize well to unseen data compared to more complex models.

### Conclusion
This project highlights the significant impact of machine learning in the realm of hate speech detection and categorization. By integrating advanced natural language processing techniques with a decision tree classifier, the model adeptly differentiates between hate speech, offensive language, and neutral content. This innovative approach not only enhances the accuracy of content moderation but also paves the way for the development of more effective tools that foster safer and more inclusive online environments.

### License
This project is licensed under the MIT License.
