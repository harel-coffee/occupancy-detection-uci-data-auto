# Room Occupancy Detection from Temperature, Light, Humidity, and Carbon Dioxide Measurements Using Deep Learning
Room occupancy detection is crucial for energy management systems. Due to the increased data available from detection sensors, machine learning models can be created and used to detect room occupancy. When a myriad amount of data is available, deep learning models might outperform traditional machine learning models. An Artificial Neural Network (ANN) was used in this article to detect room occupancy from sensor data using a simple deep learning model. In this study, a neural network model was trained on data from room temperature, light, humidity, and carbon dioxide measurements. In total, three datasets were used: one for training and two for testing the models in open and closed-door occupancy scenarios. TensorFlow, Keras, and Python were used to construct an ANN. SMOTE was used to counteract the dataset's class imbalance. Variable combinations have been tried as input features to the model in many different ways. The results show that feature selection can have a significant impact on prediction accuracy and other metrics when combined with a suitable classification model architecture. Timestamp data are omitted from this study in order to maintain the model's time independence. The ANN model's performance was evaluated using accuracy, f1-score, precision, and recall. The best predictions had a 96% to 98% average accuracy rate. Surprisingly, the model with temperature and light outperformed all the others, with an accuracy of 98%. This outperforms most of the traditional machine learning models.

Used Dataset link: https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+
