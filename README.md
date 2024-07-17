# BiostatisticsProject
## "Understanding Survival Patterns and Predictors in Primary Brain Tumor Patients (A Biostatistical Analysis of Stereotactic Radiation Therapy Outcomes)"
ABU SABRINA PERVIN, BAZZI FATEEMA, LIPPOLIS ELENA, SUFAJ DENISA
### Introduction
What is Brain Cancer?
Brain cancer refers to the presence of malignant cells in the brain, which can affect brain function and overall health.

What are Primary Brain Tumors?
Primary brain tumors originate within the brain itself rather than spreading from other parts of the body. These tumors can significantly impact the brain's functionality and are associated with varying levels of mortality.

Mortality Rate and Prevalence:
Primary brain tumors represent about 1-2% of all malignant tumors. Despite their rarity, they are associated with high mortality rates due to the critical functions of the brain regions they affect.
Types of Primary Brain Tumors:
* Meningioma: Typically benign, these tumors arise from the meninges, the layers of tissue covering the brain and spinal cord.
* Low-Grade (LG) Glioma: These are slower-growing tumors that generally have a better prognosis than high-grade gliomas.
* High-Grade (HG) Glioma: These are more aggressive and fast-growing tumors, often associated with a poorer prognosis.
* Other

### Dataset
Source of Data:
The dataset comprises information from 88 adult patients with primary brain tumors treated at the Masaryk Memorial Cancer Institute in Brno, Czech Republic. These patients were treated using stereotactic radiation methods.

Type of Study:
The data was produced by a prospective cohort study. This type of study involves following a group of patients who have already been exposed to a particular condition (in this case, primary brain tumors) and monitoring them over time to observe outcomes such as survival.

### Data description
Sample Size and Variables:
The dataset includes 88 patients with variables such as:
* Sex: Slight predominance of males over females.
* Diagnosis: Meningioma, HG Glioma, LG Glioma, or other.
* Location: Infratentorial (lower back part of the brain) or supratentorial (upper part of the brain).
* Gross Tumor Volume (GTV): Measured in cubic centimeters.
* Karnofsky Index (KI): Measures the patient's ability to perform ordinary tasks, ranging from 0 (dead) to 100 (fully able).
* Stereotactic Methods: SRS (single application of radiation) and SRT (divides total dose into several fractions).
* Time: Duration of the study from the date of diagnosis.
* Status: Whether the patient was alive at the end of the study.

Study period: July 30, 2004 - May 5, 2012.

### Research questions
* Is there a correlation between any of the factors (e.g., sex, diagnosis, tumor location, KI, GTV) and survival time?
* What is the probability of a patient surviving a certain period of time?

### Data analysis:
* Apply non-parametric methods (e.g., Mann-Whitney U test) to analyze survival data.
* Examine variables and their correlation with survival independently and through regression analysis.
* Conduct multiple hypothesis testing to explore associations between variables.
* Utilize time-to-event data and survival models, including censoring plots and confidence intervals.
* Compare median survival times between male and female patients.
* Perform logistic regression to assess the impact of different variables on survival outcomes.


References: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4749663/
