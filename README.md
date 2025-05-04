# Diabetes Prediction Using Gradient Boosting
<p>This project uses a supervised machine learning approach to predict whether a person is likely to have diabetes based on health-related features. The dataset is cleaned, scaled, balanced, and used to train a Gradient Boosting Classifier with high accuracy.</p>
<h2>📊 Project Overview</h2>
<p><li>Goal: Predict diabetes occurrence using patient diagnostic data</li>

<li>Dataset: Kaggle - Diabetes Prediction Dataset</li>

<li>Model Used: Gradient Boosting Classifier</li>

<li>Accuracy: 97.26% (Test), 97.15% (Validation)</li>

<li>Tech Stack: Python, Pandas, Scikit-learn, SMOTE, Matplotlib, Seaborn</li></p>
<h2> Steps Performed</h2>
<h3>Data Preprocessing</h3>
  <ul>
    <li>Handled missing values and verified data types</li>
    <li>Encoded categorical variables</li>
    <li>Scaled features using <code>StandardScaler</code></li>
  </ul>

  <h3>Train-Validation-Test Split</h3>
  <ul>
    <li>70% training, 15% validation, 15% testing</li>
    <li>Maintained class stratification</li>
  </ul>

  <h3>SMOTE Balancing</h3>
  <ul>
    <li>Applied Synthetic Minority Oversampling Technique to address class imbalance</li>
  </ul>

  <h3>Model Building</h3>
  <ul>
    <li>Trained <code>GradientBoostingClassifier</code> on balanced training data</li>
    <li>Tuned and validated using the validation set</li>
  </ul>

  <h3>Evaluation</h3>
  <ul>
    <li>Measured accuracy, precision, recall, and F1-score</li>
    <li>Plotted confusion matrix and ROC curve</li>
    <li>Analyzed feature importance</li>
  </ul>
