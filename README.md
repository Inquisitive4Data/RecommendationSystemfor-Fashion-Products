# RecommendationSystemfor-Fashion-Products
Fashion product Recommendation and Classification using Transfer Learning and ANNOY
introduces a hybrid framework that integrates advanced deep learning techniques for feature extraction and an efficient similarity search mechanism. The framework leverages the EfficientNetB0 model for robust feature extraction and the Annoy (Approximate Nearest Neighbors Oh Yeah) library for high-speed similarity search. Additionally, the system demonstrates remarkable accuracy in multi-class classification tasks, enabling it to classify fashion products effectively.
Dataset used 
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

Generates accurate and timely product recommendations based on user preferences.
Employs a hybrid approach combining deep learning and efficient similarity search.
Multi-Class Classification

Classifies fashion products into multiple categories with a validation accuracy of 99.79% and a validation loss of 4.8%.
Ensures high precision for e-commerce product cataloging.
Efficient Similarity Search

Utilizes the Annoy library for approximate nearest neighbor searches, ensuring scalability and fast recommendations even with large datasets.
Deep Feature Extraction

Harnesses the power of the EfficientNetB0 model to capture intricate patterns and relationships within fashion data.
Methodology
1. Feature Extraction with EfficientNetB0
EfficientNetB0, a pre-trained deep learning model, is fine-tuned to extract robust and meaningful features from fashion images.
Captures subtle details and patterns in the data for better recommendation and classification performance.
2. Similarity Search with Annoy
Annoy library is employed to perform high-speed similarity searches in the feature space.
Enables real-time recommendations by finding the nearest neighbors of a query image efficiently.
3. Multi-Class Classification
The framework is capable of categorizing products into predefined classes.
Achieves a validation accuracy of 99.79%, showcasing its ability to handle complex classification tasks.
Results
Recommendation System: Demonstrates superior performance in delivering personalized and accurate fashion recommendations.
Classification Accuracy: Achieved 99.79% validation accuracy with a validation loss of 4.8%, making it highly reliable for multi-class classification tasks.
Efficiency: The combination of EfficientNetB0 and Annoy ensures the system remains scalable and performs well with large datasets.
Installation and Usage
Prerequisites
Python 3.8+
Required Libraries:
numpy
tensorflow
annoy
scikit-learn
matplotlib
