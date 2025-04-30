# Student Score Prediction Using Linear Regression

This project uses linear regression to predict a student's score based on the number of hours they studied.

This project demonstrates how to predict a student's test score based on the number of hours they studied using **Linear Regression**.

## Steps:
1. Create a dataset of hours studied vs. scores.
2. Train a Linear Regression model.
3. Predict the score for a given number of hours studied.
4. The linear regression formula compares the predicted score with the manual calculation.

## Example Output:
- **Predicted Score for 6 hours:** 82
- **Manual Calculation:** 82

## Libraries Used:
- **pandas** for data manipulation.
- **scikit-learn** for Linear Regression model.
- **matplotlib** for visualisation (optional).

## Dependencies
- `pandas`
- `scikit-learn`
- `matplotlib`

## How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/akashkarale-255/student-score-prediction.git
    ```
2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Open and run the `student_score_prediction.ipynb` Jupyter notebook.

## Example Usage
To predict the score for a student who studied for 6 hours, run the following:
```python
# Example: Predict score for 6 hours of study
predicted_score = model.predict([[6]])  # replace model with your trained model
print(predicted_score)
