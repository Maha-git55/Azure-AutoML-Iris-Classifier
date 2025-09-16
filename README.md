
# Iris Flower Classification using Azure AutoML

This project uses **Azure Automated Machine Learning** to build a model that classifies the species of an iris flower based on features like sepal length, sepal width, petal length, and petal width.

## 📁 What's in this repository?
- `azure-model/`: Contains all the outputs and logs from the Azure Automated ML run.
- `screenshots/`: Contains screenshots of the process from the Azure ML studio.
- `iris-dataset.csv`: The dataset used for training and testing the model.

## 🚀 How was this model created?
1. The dataset was imported from Kaggle into Azure ML studio.
2. An Automated ML classification job was configured and submitted.
3. Azure AutoML automatically tried multiple algorithms (like Logistic Regression, Decision Trees, etc.) and hyperparameters.
4. The best model was selected based on the primary metric (Accuracy).

## 📊 Results & Screenshots
### 1. Submitting the Training Job
![Submitting the Job](screenshots/1-submit-job.png)

### 2. The Run in Progress (Setting Up)
![Run in Progress](screenshots/2-running.png)

### 3. Final Accuracy and Best Model
![Results](screenshots/3-results.png)

**The best model achieved an accuracy of 0.95333 (95.33%)!**

## 🔮 Future Work
- Deploy the model as a web service.
- Create a simple web app to make predictions.
