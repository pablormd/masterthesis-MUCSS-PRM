# masterthesis-MUCSS-PRM
R code and report for my Master’s Thesis, *Fraud detection performance and interpretability: controlled simulation of statistical and Machine Learning models*, with fully reproducible pipelines. Simulates linear and non-linear insurance data, trains Logistic Regression, Random Forest, XGBoost, and SVM via tidymodels, calibrates thresholds, evaluates with AUC and PR-AUC, and adds SHAP (fastshap) and DALEX for global and local explanations.

**Word file:** The Word file XXX contains the master's thesis itself, with all the necessary information in terms of requirements. Reading this file will help you understand the procedures carried out in the Rmd and html file.

**Reproducibility**
	•	**Single code source:** masterthesis_MUCSS_PRM.Rmd is self-contained and sets seeds.
	•	**Output code:** masterthesis_MUCSS_PRM.html.
	•	Execution is compute-heavy by design (tuning, SHAP, DALEX, etc.). It runs long but is correct.

 **Requirements**
	•	R (≥ 4.2) and RStudio.
	•	**OS:** Windows, macOS, or Linux.

**Installation of the packages**
Through the first visible chunk in the Rmd file, a function is defined to check, among the R packages needed to run the project, which ones have already been downloaded and which ones have not, loading the former and downloading and loading the latter.
