# Predicting-the-employee-satisfaction-levels-at-Salisfort-Motors

**A Machine Learning Approach to HR Analytics in R**

This project uses machine learning techniques to predict employee satisfaction levels at Salisfort Motors. Leveraging employee-related features such as performance scores, compensation, and departmental data, various classification models are built and evaluated to support data-driven decision-making in HR. The models were developed and tested using R.

---
Project Structure
- `data/` – Raw and processed datasets containing employee records
- `report.Rmd` – RMarkdown file containing the full analysis and modeling process
- `report.html` – Rendered HTML report with visualizations and interpretation
- `README.md` – Project description and key documentation
---

> See the full report: [`Report.html`](./Report.html)
---

# Statements 

**Acknowledgement**\
I am sincerely thank my parents and family for giving me the support and
opportunity to invest my time on learning Machine Learning and
Artificial Intelligence to apply in environmental management work.
Furthermore, I thank the Google Career Certification courses for
providing me the resources to learn {python} Programming and learn about
the Machine Learning Concepts.

**Use of generative artificial intelligence**\
Generative artificial intelligence (GenAI) was mainly used for creating
charts and adjusting visualization parameters in Python. GenAI was also
used for code debugging. However, the responses provided by GenAI were
critically judged before being implemented.

# Executive Summary 

**Problem Statement**\
Salifort Motors is a fictional French-based alternative energy vehicle
manufacturer. The HR department at Salifort Motors wants to take some
initiatives to improve employee satisfaction levels at the company. They
refer to you as a data analytics professional and ask you to provide
data-driven suggestions based on your understanding of the data. They
have the following question: what’s likely to make the employee leave
the company?

Because it is time-consuming and expensive to find, interview, and hire
new employees, increasing employee retention will be beneficial to the
company. If the data analyst can predict the factors influencing the
employees likely to quit, it might be possible to identify main factors
that contribute to their leaving.

**Project Aim and Focus**\
Goals in this project are to analyze the data collected by the HR
department and to build a model that predicts whether or not an employee
will leave the company.

**Raw data used**\
This project uses a dataset called `HR_capstone_dataset.csv`. It
represents 10 columns of self-reported information from employees of a
fictitious multinational vehicle manufacturing corporation.

**Methodology**\
The following methodology was undertaken for this project,

-   Raw data - `HR_capstone_dataset.csv` from the HR department is used
    to assess the needs of the Senior leadership team.
-   The merged data set is split into 70% training and 30% test data
    which is used to train and predict using machine learning models.
-   For this project, `Logistic Regression`, `Decision Tree` and
    `Random Forest` model were preformed to predict the employee
    satisfaction level - Analysis such as confusion matrix, feature
    importance and scoring metrics is performed to analyse the models
    performance in predicting the employee satisfaction levels and the
    main factors influencing the employees to quit.

**Results**\
Out of the models trained to predict the employee satisfaction,
`Random Forest` model outperforms other models in predicting the
employee satisfaction at Salifort Motors. The project assessment and
analysis revealed that employee disatisfaction at Salifort Motors is
mainly driven by the company poor management, overwork and poor HR work
policies.

**Key recommendations**\
Capping the number of projects per person, reviewing tenure-related
dissatisfaction (especially at the four year mark), offering incentives
for long working hours, HR department clarifying overtime work policies
and implementing a balanced evaluation system. Suggessions to introduce
structured feedback mechanisms prior to employee leaving to reduce data
leakage.
