# Heart Failure Prediction

This project predicts heart disease using several classification algorithms, achieving up to **95% accuracy**. The implementation is entirely in Python using Jupyter Notebook.

## Project Overview

The goal is to create a predictive model for heart disease based on patient health attributes such as age, sex, cholesterol level, resting blood pressure, ECG results, and more. The notebook explores, visualizes, and processes the data before training and comparing multiple machine learning classifiers.

## Dataset

- The dataset contains 918 samples with features including Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, and HeartDisease.
- Target label: `HeartDisease` (binary: 0/1)
- Missing values in RestingBP and Cholesterol are handled before model training.

## Models Used

The following machine learning models were applied and evaluated:
- **Logistic Regression**
- **K-Nearest Neighbors**
- **Decision Tree**
- **Random Forest**
- **Support Vector Machine (SVM)**

## Results

| Algorithm               | Accuracy    |
|-------------------------|------------|
| Logistic Regression     | 94.6% [1] |
| K-Nearest Neighbors     | 76.1% [1] |
| Decision Tree           | 90.2% [1] |
| Random Forest           | 95.7% [1] |
| SVM                     | 95.7% [1] |

- Best results were achieved with **Random Forest** and **SVM**, each reaching **95%+ accuracy** on the test data.[1]

## Usage

1. Clone this repository.
2. Place the `Heart_Failure_Prediction.ipynb` notebook and `heart.csv` dataset in your workspace.
3. Open the notebook in Jupyter and run the cells sequentially.
4. Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`.

## File Structure

- `Heart_Failure_Prediction.ipynb` – Main notebook with preprocessing, modeling, evaluation, and results.
- `heart.csv` – Dataset file (ensure this is in the correct path).

## Highlights

- Multiple classification models compared in detail.
- Data visualization and exploration for better insights.
- Simple code structure – beginner friendly.
- Extensive evaluation using classification metrics.

## Example

To run the notebook:

```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

```
Run each cell to see model training, accuracy, and comparisons.

## Contributing

Feel free to fork the repository and submit pull requests for improvements or new features.

## License

This project is open-source. Do credit if you use it in your work.

***

This README is tailored for sharing your Jupyter notebook project on GitHub, highlighting the models compared, implementation details, and the achieved **95% accuracy**.[1]

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/85540439/c7d25377-f972-4ca6-b813-3c13896f4cf6/Heart_Failure_Prediction.ipynb)
