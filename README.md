Business Understanding: 
➢ Problem Statement: 
The problem aims to develop a robust classification model capable of accurately 
identifying different classes of dry beans based on a comprehensive set of features. Dry 
beans are a staple food ingredient consumed worldwide, and their classification plays a 
crucial role in quality control, agricultural research, and food processing industries. 
Therefore, the objective is to leverage machine learning techniques to automate the 
classification process, enabling efficient and accurate identification of bean types. 
By developing a robust classification model, this project aims to streamline the 
process of identifying different classes of dry beans, thereby enhancing productivity, 
reducing manual effort, and facilitating better decision-making in industries related to 
agriculture, food processing, and quality assurance. 
 Data Understanding: 
• Seven different types of dry beans were used in this research, taking into 
account features such as form, shape, type, and structure by the market 
situation. A computer vision system was developed to distinguish seven 
different registered varieties of dry beans with similar features to obtain 
uniform seed classification.  
• For the classification model, images of 13,611 grains of 7 different registered 
dry beans were taken with a high-resolution camera. Bean images obtained 
by computer vision system were subjected to segmentation and feature 
extraction stages, and a total of 16 features; 12 dimensions and 4 shape 
forms, were obtained from the grains. 
• The class variable represents the target label to be predicted for each bean sample. 
The dataset includes multiple class labels, including Dermason, Sira, Seker, Horoz, 
Cali, Barbunya, and Bombay. Each class label corresponds to a distinct type or 
variety of dry beans.
Model Building: 
histplot 
For the model-building stage, the KNN (K-Nearest Neighbors) classifier was selected 
as the algorithm of choice for solving the classification problem of identifying different 
types of dry beans based on their characteristics. 
To start, the dataset was divided into two main subsets: the training set and the testing 
set. The training set, which comprised the majority of the data, was used to train the 
KNN classifier, while the testing set, representing a smaller portion of the data, was 
held back to evaluate the trained model's performance. 
During the training phase, the KNN algorithm effectively learns the underlying patterns 
and relationships in the training data by memorizing the feature values and 
corresponding class labels of the training instances. This process allows the model to 
make predictions for unseen data points during the testing phase. 
In terms of implementation, various techniques were employed to enhance the 
performance of the KNN classifier
