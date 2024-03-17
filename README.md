# Student Loan Risk Assessment with Deep Learning

This project develops a deep learning model to assess the risk associated with student loans. The model predicts the likelihood of loan repayment success based on various features such as payment history, GPA ranking, degree type, and more. The project is designed to aid financial institutions in making informed decisions and to help students understand their loan repayment capabilities.

## Project Structure

The repository consists of the following main components:

- `student_loans_with_deep_learning.ipynb`: Jupyter notebook containing the full project from data preprocessing to model evaluation and prediction.
- `student_loans.csv`: Dataset used for training and testing the neural network model.
- `student_loans.keras`: The saved neural network model ready for predictions. This file will be generated once you run the notebook, I recommend using Google's Colaboratory.
- `README.md`: This file, providing an overview of the project, its structure, and acknowledgments.

## Data Source

The dataset `student-loans.csv` is used for this project, which contains anonymized data related to student loans and various features that may influence loan repayment success.

## Model Overview

The deep learning model is built using TensorFlow and Keras. It features a sequential architecture with two hidden layers and binary classification output to predict loan repayment success.

## Acknowledgments

The development of this project was assisted by Data Insight AI (ChatGPT by OpenAI, customized by myself to serve this type of challenges), which provided guidance on data preprocessing, model creation, evaluation, and prediction steps. The interaction with Data Insight AI was solely for educational and troubleshooting purposes, with no direct code contributions from external collaborators.

### Note on Code Originality

- **Data Preprocessing and Analysis:** The code for data loading, cleaning, and preparation is based on standard practices commonly found in data science literature and was adapted for the specific needs of this project.
- **Model Development and Evaluation:** The architecture and training process of the neural network model were developed with insights from Data Insight AI, following general guidelines provided by TensorFlow and Keras documentation. Modifications were made to tailor the model to the project's specific requirements.

No external code sources were used beyond the guidance provided by TensorFlow, Keras documentation, and the assistance of Data Insight AI. All code in `student_loans_with_deep_learning.ipynb` was authored by me, with conceptual guidance and troubleshooting support from Data Insight AI.

## Usage

To replicate or further develop this project:

1. Ensure you have Python 3 and Jupyter Notebook installed.
2. Install necessary libraries: TensorFlow, Keras, Pandas, Scikit-learn.
3. Run the Jupyter Notebook `student_loans_with_deep_learning.ipynb`.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.

