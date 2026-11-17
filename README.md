Over and Under Sampling Using Python

📌 Project Overview

This project demonstrates different sampling techniques using Python. It focuses on selecting representative samples from datasets and handling imbalanced datasets using over-sampling and under-sampling methods.

The project explores various sampling approaches with practical examples and data visualizations.

🎯 Objectives

- Understand different sampling techniques.
- Perform random and stratified sampling.
- Implement reservoir sampling.
- Understand random over-sampling and under-sampling.
- Apply Tomek Links for undersampling.
- Use SMOTE to balance imbalanced datasets.

🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn

📚 Topics Covered

1. Simple Random Sampling
2. Stratified Sampling
3. Reservoir Sampling
4. Random Under-sampling
5. Random Over-sampling
6. Tomek Links Under-sampling
7. SMOTE (Synthetic Minority Over-sampling Technique)

📊 Key Analysis and Results

- Selected 100 random samples from a dataset.
- Applied stratified sampling with a 75:25 train-test split.
- Implemented reservoir sampling to select 5 elements from a stream of 10,000 elements.
- Generated an imbalanced dataset with 90 majority-class and 10 minority-class samples.
- Random under-sampling reduced the dataset to 20 samples.
- Random over-sampling increased the dataset to 180 samples.
- Tomek Links reduced the dataset from 100 to 99 samples.
- SMOTE balanced the dataset to 90 samples in each class.

💻 How to Run

1. Clone or download this repository.
2. Open the notebook using Google Colab or Jupyter Notebook.
3. Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

4. For the AutoScout24 dataset section, place "autoscout24.csv" inside the required "../data/" folder.
5. Run the notebook cells sequentially.

📈 Outcome

The project demonstrates how different sampling techniques are used to select data and handle class imbalance. It provides practical understanding of data preprocessing techniques used in Machine Learning.

📝 Conclusion

This project helped develop practical knowledge of sampling methods and dataset balancing techniques using Python. It demonstrates how sampling approaches can improve dataset preparation for Machine Learning applications.

