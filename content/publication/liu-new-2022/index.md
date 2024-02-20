---
title: New onset delirium prediction using machine learning and long short-term memory
  (LSTM) in electronic health record
authors:
- Siru Liu
- Joseph J. Schlesinger
- Allison B. McCoy
- Thomas J. Reese
- Bryan Steitz
- Elise Russo
- Brian Koh
- Adam Wright
date: '2022-12-01'
publishDate: '2024-02-20T22:32:19.407323Z'
publication_types:
- article-journal
publication: '*Journal of the American Medical Informatics Association: JAMIA*'
doi: 10.1093/jamia/ocac210
abstract: "OBJECTIVE: To develop and test an accurate deep learning model for predicting
  new onset delirium in hospitalized adult patients. METHODS: Using electronic health
  record (EHR) data extracted from a large academic medical center, we developed a
  model combining long short-term memory (LSTM) and machine learning to predict new
  onset delirium and compared its performance with machine-learning-only models (logistic
  regression, random forest, support vector machine, neural network, and LightGBM).
  The labels of models were confusion assessment method (CAM) assessments. We evaluated
  models on a hold-out dataset. We calculated Shapley additive explanations (SHAP)
  measures to gauge the feature impact on the model. RESULTS: A total of 331 489 CAM
  assessments with 896 features from 34 035 patients were included. The LightGBM model
  achieved the best performance (AUC 0.927 [0.924, 0.929] and F1 0.626 [0.618, 0.634])
  among the machine learning models. When combined with the LSTM model, the final
  model's performance improved significantly (P = .001) with AUC 0.952 [0.950, 0.955]
  and F1 0.759 [0.755, 0.765]. The precision value of the combined model improved
  from 0.497 to 0.751 with a fixed recall of 0.8. Using the mean absolute SHAP values,
  we identified the top 20 features, including age, heart rate, Richmond Agitation-Sedation
  Scale score, Morse fall risk score, pulse, respiratory rate, and level of care.
  CONCLUSION: Leveraging LSTM to capture temporal trends and combining it with the
  LightGBM model can significantly improve the prediction of new onset delirium, providing
  an algorithmic basis for the subsequent development of clinical decision support
  tools for proactive delirium interventions."
tags:
- Adult
- deep learning
- delirium
- Delirium
- Electronic Health Records
- explainable machine learning
- Humans
- Machine Learning
- Memory
- Short-Term
- Neural Networks
- Computer
- predictive models
---
