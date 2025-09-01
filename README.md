Introduction  
Cardiovascular diseases (CVDs) remain the foremost cause of death globally, accounting for nearly 17.9 million fatalities each year, according to the World Health Organization. The asymptomatic progression of these conditions often delays diagnosis, making early detection essential for reducing risk and improving outcomes. Traditional diagnostic approaches rely on rule-based systems and predefined thresholds that may overlook complex, non-linear interactions among patient features.

In response, machine learning (ML) and deep learning (DL) methods have gained momentum for their ability to uncover hidden patterns within clinical data. This project investigates a broad set of models including Logistic Regression, Random Forest, Support Vector Machines, K-Nearest Neighbors, Gaussian Process Classifier, LightGBM, TabNet, and categorical embedding networks, to assess their effectiveness in predicting heart disease from structured patient information.

A key novelty of this work lies in its comprehensive approach that goes beyond raw performance. In addition to evaluating accuracy, the project places strong emphasis on identifying and mitigating overfitting, which is especially critical when deploying models in real-world clinical environments. The risk of overfitting not only reduces generalization to unseen populations but also compromises clinical reliability. Alongside this, we explore model interpretability through SHAP and LIME to ensure that the decision-making process remains transparent and justifiable to practitioners.
The goals of this project are to rigorously benchmark both classical and advanced models for cardiovascular risk prediction, to understand and control overfitting across these models, to examine generalization performance across datasets, and to provide interpretable insights that enhance the clinical relevance of the predictions.

1.1 Research Questions 
To address the challenges in heart disease prediction, we have formulated the following research questions:

RQ1: What patterns and correlations among clinical parameters (e.g., age, cholesterol, blood pressure, ECG results) are most strongly associated with the severity of cardiovascular disease, and how can these insights inform clinical prioritization or resource allocation? 

RQ2: On benchmark datasets such as UCI Heart Disease, do deep learning models designed for tabular data(e.g., Category Embedding Models, TabNet) outperform classical machine learning models in predictive performance?

RQ3: How well do predictive models trained on one clinical dataset perform when tested on a separate dataset with differing patient characteristics, and what does this indicate about their robustness for broader clinical deployment?

RQ4: How can overfitting and lack of interpretability be addressed in the development of predictive models for cardiovascular disease, and how might these improvements impact early identification of high-risk individuals compared to traditional clinical scoring methods?

These research questions aim to explore key aspects of applying machine learning to cardiovascular disease prediction: interpretability, generalization, model performance, and clinical applicability. RQ1 focuses on identifying which clinical features are most strongly linked to disease severity, helping models provide insights that can support patient care decisions. RQ2 investigates whether deep learning models designed for tabular data can offer measurable performance improvements over traditional methods when evaluated on a benchmark dataset. RQ3 examines the ability of models to generalize across datasets with different patient populations, which is essential for safe and scalable deployment. Finally, RQ4 addresses the challenges of overfitting and lack of interpretability and how they can contribute to building models that are both reliable and clinically transparent. This would further lead to better patient outcomes and more efficient resource allocation.


Team Members:
Tanvi Mehta, Savali Deshmukh, Shivani Suryawanshi
