1. Introduction  

Cardiovascular diseases (CVDs) continue to be the leading cause of mortality worldwide, responsible for approximately 17.9 million deaths annually, or 31% of all global deaths, according to the World Health Organization. These diseases often progress silently and unpredictably, making early and accurate diagnosis a critical factor in improving patient outcomes. Traditional diagnostic methods rely heavily on subjective assessments and static threshold-based risk scores, which often fail to capture the complex interactions between demographic, behavioral, and clinical factors.

The primary objective of this project is to explore whether recent advancements in machine learning and deep learning—specifically TabNet, category embedding models, and LightGBM, alongside classical algorithms like Random Forest, Support Vector Machines (SVM), k-Nearest Neighbors (KNN), and Gaussian Processes—can significantly improve predictive performance and clinical interpretability for heart disease prediction.

Another key goal is to examine the generalization capability of these predictive models. We aim to investigate how models trained on one dataset perform when applied to a separate, larger, and more diverse dataset. This evaluation is crucial to determine the robustness and real-world applicability of the models across varied populations and clinical settings.

2 Research Questions 

To address the challenges in heart disease prediction, we have formulated the following research questions:

RQ1: What patterns and correlations among clinical parameters (e.g., age, cholesterol, blood pressure, ECG results) are most strongly associated with the severity of cardiovascular disease, and how can these insights inform clinical prioritization or resource allocation?
RQ2: Do deep learning architectures specifically designed for tabular clinical data (e.g., Category Embedding Models, TabNet) outperform classical models in predictive accuracy for heart disease detection?
RQ3: How well do predictive models trained on one clinical dataset perform when tested on a separate dataset with differing patient characteristics, and what does this indicate about their robustness for broader clinical deployment?
RQ4: Based on the most accurate predictive model, how would early intervention strategies shift if high-risk individuals were identified using machine learning-based screening rather than traditional clinical scoring tools?

The proposed research questions address key challenges in cardiovascular disease prediction by focusing on model interpretability, performance, generalization, and clinical impact. RQ1 aims to identify critical clinical factors influencing disease severity, enabling models to provide actionable insights for targeted interventions. RQ2 investigates whether advanced models for tabular data offer meaningful performance gains over traditional methods, validating their practical utility. RQ3 examines the generalization capabilities of predictive models across datasets with varying clinical characteristics, ensuring robustness for broader healthcare applications. Finally, RQ4 assesses how integrating machine learning-based screening could improve early detection and intervention strategies, leading to better patient outcomes and more efficient resource allocation.
