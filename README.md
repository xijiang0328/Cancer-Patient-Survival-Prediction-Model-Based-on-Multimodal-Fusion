# Cancer-Patient-Survival-Prediction-Model-Based-on-Multimodal-Fusion
Developed a multimodal survival prediction model using clinical and RNA-seq data from the IMvigor210 cohort. Applied variance filtering and PCA for dimensionality reduction, followed by 5-fold cross-validated LightGBM training. Generated individual risk scores and evaluated performance using C-index and Kaplan–Meier survival analysis.
How to Run
1.Install dependencies:    pip install pandas numpy lightgbm lifelines scikit-learn pyreadr
2.Place IMvigor210 Rdata file in project directory
3.Run the pipeline step-by-step from Step 1 to Step 6
