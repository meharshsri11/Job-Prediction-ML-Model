# Job Prediction Model

## Project Overview
**Job Prediction Model** is a student project that focuses on **predicting suitable job roles** based on student data. The project involves data collection, preprocessing, feature engineering, exploratory data analysis (EDA), and model building to predict job roles for students.

---

## Dataset
The dataset includes student information with the following columns:

- **Student ID** – Unique identifier for each student
- **Name** – Student’s full name
- **Branch** – Academic branch/department
- **CGPA** – Cumulative grade point average
- **Certifications** – Number or type of certifications
- **Aptitude Score** – Score in aptitude tests
- **Project Tech** – Technologies used in projects
- **Short Skills Rating** – Skill rating (technical/soft skills)
- **Favorite Language** – Preferred programming language
- **Preferred Work Mode** – e.g., Remote, Hybrid, On-site
- **Experience/Internship** – Years of experience or internships
- **Job Role** – Target column for prediction (not in raw dataset)

> The raw dataset does **not include the Job Role**. It is generated from student features using a weighted logic-based function.

---

## Project Structure

Job_Prediction_Model/
│
├── students_raw.csv # Raw student dataset
├── output/ # Folder for visualizations and model outputs
├── job_role_prediction.ipynb # Jupyter Notebook with complete workflow
├── README.md # Project documentation
└── requirements.txt # Required Python packages

yaml
Copy code

---

## Features and Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables (Label Encoding)
   - Feature scaling (Standardization)

2. **Exploratory Data Analysis (EDA)**
   - Visualizations: Histograms, Boxplots, Heatmaps
   - Insights on CGPA, Branch distribution, Skills, Experience

3. **Modeling**
   - Logistic Regression / Other classifiers
   - Predicting job roles based on student attributes

4. **Output**
   - Predicted job roles
   - Visualization of feature importance and distributions

---

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd Job_Prediction_Model
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook job_role_prediction.ipynb and run all cells to see the full workflow and results.

Dependencies
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

Jupyter Notebook

Author
Harsh Srivastava – Student & Project Creator
