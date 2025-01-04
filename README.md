# Home Run Prediction Using Machine Learning

This project explores the prediction of home runs in Major League Baseball (MLB) using Statcast data. Leveraging advanced baseball analytics, the study employs machine learning models to classify batted ball outcomes and identify key features that influence home run events. 

## Project Description

The project utilizes a dataset from the 2020 MLB season containing detailed batted ball statistics. Two machine learning models, Random Forest and Naive Bayes, were trained and evaluated to classify whether a batted ball results in a home run or not. 

The Random Forest model provided feature importance insights, highlighting exit velocity and launch angle as the most significant factors. While it excelled in predicting non-home-run events, the Naive Bayes model outperformed in identifying home runs and showed greater computational efficiency.

Key components of the project include:
- Data preprocessing, including feature selection and engineering.
- Implementation and evaluation of Random Forest and Naive Bayes models.
- Performance comparison using metrics like accuracy, precision, and recall.
- Feature importance analysis to derive actionable insights for baseball strategies.

## Code Details

The project code is provided in a Jupyter Notebook (`CSE498_FinalProject.ipynb`) and includes the following sections:
1. **Data Preprocessing**: Feature selection, encoding, and integration of ballpark dimensions.
2. **Model Training**: Training Random Forest and Naive Bayes classifiers.
3. **Evaluation**: Metrics computation, confusion matrix visualization, and cross-validation.
4. **Feature Engineering**: Enhanced predictive capabilities through statistical transformations.
5. **Insights and Results**: Analysis of model outputs and feature importance rankings.

## Results Summary

- **Random Forest Model**: High overall accuracy (97.33%) and precision for non-home-run events. Feature importance analysis identified exit velocity and launch angle as pivotal factors.
- **Naive Bayes Model**: Superior recall for home runs (88.39%), computational efficiency, and balanced performance in imbalanced datasets.
- **Model Comparison**: Naive Bayes was preferred for its computational efficiency and better recall in home run prediction, while Random Forest provided valuable feature insights.

## References

This project builds upon prior research in baseball analytics and incorporates publicly available data from Kaggle and MLB Statcast. Detailed references can be found in the accompanying report.

---

For more details, refer to the full project report (`Homerun_Prediction_Report.pdf`) and code (`CSE498_FinalProject.ipynb`).
