## Unveiling Predictive Factors in Apple Quality: Leveraging LIME, SHAP, and the Synergy of Machine Learning Models and Artificial Neural Networks

## Overview
This repository contains the implementation and analysis from the research paper titled *"Unveiling Predictive Factors in Apple Quality: Leveraging LIME, SHAP, and the Synergy of Machine Learning Models and Artificial Neural Networks"*, presented at the 2024 6th International Conference on Electrical Engineering and Information & Communication Technology (ICEEICT) held at the Military Institute of Science and Technology (MIST), Dhaka, Bangladesh. The study, authored by Rituparna Chowdhury, Rudra Das, Fowzia Binta Faruk Ananna, Arnob Saha, Sadia Nawar, and Md. Hamid Hosen, explores advanced techniques for apple quality assessment using machine learning and explainable AI (XAI).

- **DOI**: 10.1109/ICEEICT62016.2024.10534426
- **Conference**: 2024 6th International Conference on Electrical Engineering and Information & Communication Technology (ICEEICT)
- **Publication Date**: May 2024
- **ISBN**: 979-8-3503-8577-9/24/$31.00 ©2024 IEEE

## Research Objective
The study addresses the limitations of traditional apple quality assessment methods (e.g., physical and chemical analyses), which are time-consuming and damaging to samples. It proposes non-destructive techniques, focusing on machine learning algorithms, to accurately classify apple quality into "good" and "bad" categories. The research evaluates multiple models and employs XAI tools (LIME and SHAP) to enhance interpretability.

## Methodology
- **Dataset**: A Kaggle dataset with 4000 instances, featuring nine attributes (ID, size, weight, sweetness, crunchiness, juiciness, ripeness, acidity, and quality), where quality is the target variable (good = 1, bad = 0).
- **Data Preprocessing**: Handled missing data, duplicates, and scaled features to ensure consistency.
- **Data Split**: 80% (3200 instances) for training, 20% (800 instances) for testing.
- **Models Evaluated**:
  - Random Forest Classifier (RF)
  - K-Nearest Neighbors Classifier (KNN)
  - Support Vector Classifier (SVC)
  - Extreme Gradient Boosting Classifier (XGB)
  - Light Gradient Boosting Machine Classifier (LGBM)
  - Artificial Neural Network (ANN)
  - Voting Classifier (ensemble of RF, SVC, XGB)
- **XAI Techniques**: LIME and SHAP for interpreting model decisions.

## Key Findings
- **Best Performing Model**: The Artificial Neural Network (ANN) achieved the highest accuracy of **92.87%**, with matching precision, recall, and F1 score.
- **Other Models**:
  - Voting Classifier: 92.50% accuracy
  - SVC: 92.00% accuracy
  - XGB: 91.13% accuracy
  - RF, KNN, LGBM: Accuracies ranging from 90.38% to 90.75%
- **Feature Importance**: XAI analysis identified "size" as the most influential feature, with juiciness, acidity, sweetness, crunchiness, and weight also significant.
- **Training Stability**: ANN accuracy and loss stabilized after approximately 200 epochs.

## Tables
- **Table I**: Train/test data split (80%/20%).
- **Table II**: Hyperparameters and training scores for each model.
- **Table III**: Performance evaluation (accuracy, precision, recall, F1 score).

## Conclusion
The research demonstrates that ANN outperforms other machine learning models for apple quality classification, offering a non-destructive, efficient alternative to traditional methods. XAI tools (LIME and SHAP) provide valuable insights into model decisions, with "size" emerging as a key predictor. Future work could expand the dataset, incorporate real-world data, and explore deep learning or IoT integration.

## Keywords
- Adaptation models
- Machine learning algorithms
- Biological system modeling
- Static VAr compensators
- Artificial neural networks
- Boosting
- Vectors
- Apple quality
- Fruit classification
- XAI
- LIME
- SHAP

## References
Refer to the original paper for a detailed list of references, including works by Leiva-Valenzuela et al., Sun et al., and others cited in the literature review. Additionally:
- Hosen, Md. Hamid, et al. "Predicting Stress in Bangladeshi University Students: A LIME-Interpretable Machine Learning Approach." *Proceedings of the 2nd International Conference on Big Data, IoT, and Machine Learning: BIM 2023*, East Delta University, Bangladesh, 2024.

## Usage
This repository may include code, datasets, or pre-trained models (if available). Please refer to specific files or instructions for setup and execution. For the dataset, access the Kaggle link: [Apple Quality](https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality).

## Contact
- Rituparna Chowdhury: rituparna.chy550@gmail.com
- Rudra Das: dasrudra738@gmail.com
- Fowzia Binta Faruk Ananna: fowziabintafarukanannya@gmail.com
- Arnob Saha: sahaarnob73@gmail.com
- Sadia Nawar: sadianawar2019@gmail.com
- Md. Hamid Hosen: mdhamidhosen4@gmail.com

## License
©2024 IEEE. This work is subject to the IEEE copyright and usage policies.
