# Milk-Quality-Classification
The primary goal of this project is to design a robust machine learning model capable of accurately classifying milk quality into three categories: low quality, medium quality, and high quality. 

## Objective
The primary goal of this project is to design a robust machine learning model capable of accurately classifying milk quality into three categories: low quality, medium quality, and high quality. The dataset, manually collected from observations, consists of 429 instances of low quality, 374 instances of medium quality, and 256 instances of high quality milk. The central objective is to create a model that exhibits good generalization, making proper classifications for new milk samples based on key features.

## Data Set
The milk dataset comprises 1059 samples, with 7 independent variables:
1. **PH:** pH of the milk, ranging from 3 to 9.5.
2. **Temperature:** Temperature of the milk, ranging from 34°C to 90°C.
3. **Taste:** Binary variable (1 for good taste, 0 for bad taste).
4. **Odor:** Binary variable (1 for good odor, 0 for bad odor).
5. **Fat:** Binary variable (1 for good fat content, 0 for bad fat content).
6. **Turbidity:** Binary variable (1 for good turbidity, 0 for bad turbidity).
7. **Color:** Color of the milk, ranging from 240 to 255.
8. **Grade:** Target variable with values: low_quality, medium_quality, or high_quality.

## Machine Learning Techniques Used
The project involves the application of various machine learning techniques:
- Data Preprocessing
- Feature Selection
- Model Building

## Model Performance
Using the Decision Tree technique, the project achieved the highest accuracy of 98%, indicating the effectiveness of Decision Tree algorithm in classifying milk quality. Other techniques, such as Logistic Regression and LDA, were also employed.

## Repository Structure
1. **Code:** Contains the source code for data preprocessing, feature selection, and model building.
2. **Data:** Includes the dataset used for training and testing the models.
3. **Documentation:** Comprehensive documentation explaining the dataset, feature details, model implementation, and results.
4. **Results:** Displays performance metrics and results obtained during testing and evaluation.

## How to Use
1. Clone the repository to your local machine.
2. Explore the dataset in the 'Data' folder for understanding the input data.
3. Refer to the documentation for step-by-step instructions on running the code, training models, and interpreting results.
