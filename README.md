
# Recruitment Data Analysis

This repository contains a comprehensive analysis of a recruitment dataset, focusing on predicting hiring decisions based on candidate attributes. The goal is to gain deeper insights into the factors influencing hiring decisions and to build a robust predictive model.

## Dataset Description

The dataset contains the following features:

- **Age**: Age of the candidate.
- **Gender**: Gender of the candidate (0: Male, 1: Female).
- **EducationLevel**: Highest level of education attained by the candidate.
- **ExperienceYears**: Number of years of professional experience.
- **PreviousCompanies**: Number of previous companies where the candidate has worked.
- **DistanceFromCompany**: Distance in kilometers from the candidate's residence to the hiring company.
- **InterviewScore**: Score achieved by the candidate in the interview process.
- **SkillScore**: Assessment score of the candidate's technical skills.
- **PersonalityScore**: Evaluation score of the candidate's personality traits.
- **RecruitmentStrategy**: Strategy adopted by the hiring team for recruitment.
- **HiringDecision**: Outcome of the hiring decision (0: Not hired, 1: Hired).

## Notebook Contents

The Jupyter notebook `advanced_recruitment_analysis.ipynb` includes the following sections:

### 1. Data Preprocessing and Initial Analysis

- Loading the dataset
- Checking for missing values
- Summary statistics

### 2. Data Visualization

- Distributions of numerical features
- Relationships with the target variable (hiring decision)

### 3. Correlation Analysis

- Heatmap of the correlation matrix to understand relationships between features

### 4. Feature Importance

- Using a Random Forest model to determine the importance of each feature in predicting the hiring decision

### 5. Model Building and Evaluation

- Building a Random Forest model
- Evaluating the model performance using accuracy, classification report, and confusion matrix

### 6. Hyperparameter Tuning

- Using GridSearchCV to find the best hyperparameters for the Random Forest model
- Evaluating the best model

### 7. Insights and Conclusions

- Key insights from the analysis
- Important features for predicting hiring decisions
- Model performance and conclusions

## Getting Started

### Prerequisites

- Python 3.7+
- Jupyter Notebook or Jupyter Lab

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/debjit-mandal/recruitment-analysis.git
   cd recruitment-analysis
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook advanced_recruitment_analysis.ipynb
   ```

2. Run the cells sequentially to perform the analysis.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or additions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the dataset providers and the open-source community for their valuable resources and contributions.
- The dataset can be found in Kaggle: [💼 Predicting Hiring Decisions in Recruitment Data](https://www.kaggle.com/datasets/rabieelkharoua/predicting-hiring-decisions-in-recruitment-data)
