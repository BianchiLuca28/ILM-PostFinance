# Explainable AI for Credit Scoring with Ontology Integration

This project aims to provide a transparent and explainable AI solution for credit scoring, allowing financial operators to understand and relay AI predictions to customers effectively. The system integrates machine learning models, Shapley values for feature explainability, and ontology-based reasoning to enhance the interpretability of predictions.

---

## Features

- **Explainable Machine Learning Model**: Predict customer creditworthiness with explanations for each decision.
- **Ontology Integration**: Enhance explainability by linking features to a domain-specific ontology.
- **Interactive Streamlit Interface**: Demonstrate predictions and explanations in a user-friendly web app.

---

## Repository Structure

The repository is organized into the following folders:

- **`database/`**: Contains the datasets and models used in the project.
- **`notebooks/`**: Contains the Jupyter notebooks for the various stages of the project:
  - `loading_dataset.ipynb`: Transforming the dataset in a more friendly format to be then analyzed.
  - `exploratory_data_analysis.ipynb`: Exploratory Data Analysis (EDA) notebook.
  - `preprocessing.ipynb`: Data preprocessing pipeline, including cleaning and feature engineering.
  - `model.ipynb`: Machine learning model training and SHAP explainability analysis.
- **`ui/`**: Contains the Streamlit interface components and code for interacting with the trained model.
- **`requirements.txt`**: Python dependencies required to run the project.
- **`README.md`**: Project documentation (this file).

---

## Getting Started

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/BianchiLuca28/ILM-PostFinance.git
cd ILM-PostFinance
```

### 2. Set Up the Python Environment

Activate the Python environment:

Linux/Mac:

```bash
source env/bin/activate
```

Windows:

```bash
.\env\Scripts\activate
```

#### Install the required libraries:

```bash
pip install -r requirements.txt
```

### 3. Launch the Streamlit App

The project includes a Streamlit interface for showcasing predictions and explanations.

#### Run the app:

```bash
streamlit run path/to/streamlit_app.py
```

Open the link provided in the terminal to interact with the application.

#### Requirements

This project requires Python 3.8 or higher. The dependencies are listed in **requirements.txt**.

## Contributors

- **Luca Bianchi**  
  FHNW University, Independent Learning Module  
  Email: luca.bianchi@students.fhnw.com
- **Stanislav Teghipco**  
  FHNW University, Independent Learning Module  
  Email: stanislav.teghipco@students.fhnw.ch
- **Angelica Berdini**  
  FHNW University, Independent Learning Module  
  Email: angelica.berdini@students.fhnw.ch

## License

This project is licensed under the MIT License.
