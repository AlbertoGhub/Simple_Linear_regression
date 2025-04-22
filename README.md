
# Simple Linear Regression

## 📘 Description

This project demonstrates the process of building a **Simple Linear Regression model** using Python and scikit-learn. The aim is to predict student scores based on the number of hours studied — a classic beginner-friendly use case.

The process is divided into four key stages, commonly used in most machine learning workflows:

1. **Data Preprocessing**  
   - Import libraries  
   - Load the dataset  
   - Check for missing values  
   - Split the data into training and test sets  
   - (Optional) Apply feature scaling  

2. **Model Training**  
   A simple linear regression model is trained using the `LinearRegression()` class from `sklearn.linear_model`. The model is fitted to the training data using the `.fit()` method.

3. **Prediction**  
   The model is used to make predictions on unseen data, storing the results in `Y_pred`.

4. **Visualisation**  
   Scatter plots are generated using `matplotlib` to visualise both the training and test results, helping us assess how well the model fits the data.

5. **Conclusion and Interpretation**  
   Drawing conclusions and interpreting results is a crucial step in any machine learning project. This section provides insights based on the model's performance metrics and visualisations, highlighting how well the regression line fits the data and what the results mean in context.

# 🔍 Objective

  To create a **linear model** that can predict the score a student is likely to achieve based on the number of hours studied.
# 🚀 How to Run

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt` or `conda install --file requirements.yml`
## 👌 Explanation

```pip```: For standard Python virtual environments (requirements.txt)

```conda```: If you're using Anaconda/Miniconda and prefer to work with .yml environment files (requirements.yml)
# 📈 Output Plot

As can be observed, there is a strong linear relationship between the independent variable (X) and the dependent variable (Y). This indicates that the linear regression model performs well on the test data, demonstrating good generalisation, low error, and a strong linear fit.

### Training set
![Training set](Images/training_plot.png)

### Testing set
![Alt Text](/Users/alberto/Documents/Coding/7_DataScience_ML_projects/Linear_Regression/1_Simple_Linear_regression/Images/testing_results.png)

## 🧪 Model Performance (test set):

- ```MAE```: 4.13

- ```MSE```: 20.33

- ```R² Score```: 0.94


## 📦 Libraries Used

- ```pandas```

- ```numpy```

- ```matplotlib```

- ```scikit-learn```
## 🗂️ File Structure

| File/Folder        | Description                    |
|--------------------|--------------------------------|
| `main.py`          | Main script for loading, training, and plotting |
| `data/`            | Contains the dataset           |
| `images/`          | Saved output visualisations    |
| `requirements.txt` | Project dependencies           |

## 👨‍💻 Author

Made with ❤️ by Alberto AJ - AI/ML Engineer.
