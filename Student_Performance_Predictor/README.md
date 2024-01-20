# Question Answer Success Predictor

This directory houses the `Question_Answer_Success_Predictor.ipynb` notebook, which is centered around building a classifier to estimate the likelihood of students correctly answering quiz questions. This predictive model takes into account individual student performance metrics and the inherent complexity of the questions.

## Notebook Insight

This notebook guides you through the process of creating a predictive model using `sklearn` pipeline. It encapsulates data preprocessing, feature extraction, and the deployment of a K-Nearest Neighbors classifier. The model considers the following aspects:

- **Student Data**: Includes gender, average response time, and the average correctness of previously answered questions.
- **Question Complexity**: Evaluated based on the allocated time for the question, the length of the question, and the cumulative length of the answer choices.

## Getting Started

To engage with the notebook:

1. Make sure Python and Jupyter are installed on your system.
2. Clone the repository to your local environment.
3. Navigate to the `Student_Performance_Predictor` directory.
4. Open Jupyter Notebook and load the `Question_Answer_Success_Predictor.ipynb` file.
