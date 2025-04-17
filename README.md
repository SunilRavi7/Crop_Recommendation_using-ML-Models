<!-- README.html for Crop Recommendation System -->

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Crop Recommendation System</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 40px;
      line-height: 1.6;
      background-color: #f4f4f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #005f73;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
      margin: 10px 0;
    }
    code {
      background: #eee;
      padding: 2px 5px;
      border-radius: 4px;
    }
    .section {
      background: #ffffff;
      padding: 20px;
      margin-bottom: 30px;
      border-radius: 10px;
      box-shadow: 0px 0px 8px rgba(0,0,0,0.1);
    }
    a {
      color: #0a9396;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <div class="section">
    <h1>🌾 Crop Recommendation System using Machine Learning</h1>
    <img src="https://i.ibb.co/qB6yZhf/crop-main.jpg" alt="Crop Recommendation System Banner">
    <p>This project predicts the most suitable crop to grow based on soil nutrients, weather parameters, and rainfall using multiple ML models. It's built to assist farmers and agricultural scientists with accurate recommendations.</p>
  </div>

  <div class="section">
    <h2>📌 Features</h2>
    <ul>
      <li>Analyzes soil parameters: Nitrogen, Phosphorus, Potassium</li>
      <li>Includes temperature, humidity, pH, and rainfall as inputs</li>
      <li>Trained with 5 ML models: Decision Tree, SVM, Naive Bayes, Logistic Regression, Random Forest, and XGBoost</li>
      <li>Model accuracy comparison included</li>
      <li>Heatmap for feature correlation</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧪 Requirements</h2>
    <pre><code>Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
pickle
</code></pre>
    <p>Install all dependencies using:</p>
    <pre><code>pip install -r requirements.txt</code></pre>
  </div>

  <div class="section">
    <h2>📂 Dataset</h2>
    <p>The dataset used is <code>Crop_recommendation.csv</code> which contains information about 7 features and 1 target label (crop name). Make sure the dataset is placed in your working directory.</p>
  </div>

  <div class="section">
    <h2>💻 How to Run</h2>
    <p><strong>Clone the repository:</strong></p>
    <pre><code>git clone https://github.com/yourusername/crop-recommendation-ml.git</code></pre>
    
    <p><strong>Or fork it for your own use:</strong></p>
    <pre><code>Click on the "Fork" button on top-right of the repository page on GitHub</code></pre>
    
    <p><strong>Run the main script:</strong></p>
    <pre><code>python crop_recommendation_system_based_on_machine_learning_using_python.py</code></pre>
  </div>

  <div class="section">
    <h2>📊 Visualizations</h2>
    
    <h3>1. Heatmap - Feature Correlation</h3>
    <img src="https://i.ibb.co/wKXTZQ0/heatmap.png" alt="Heatmap showing feature correlation">
    
    <h3>2. Accuracy Comparison of ML Models</h3>
    <img src="https://i.ibb.co/ySXzM2c/model-accuracy.png" alt="Barplot comparison of model accuracies">
  </div>

  <div class="section">
    <h2>🚀 Model Highlights</h2>
    <ul>
      <li>Best-performing models are Random Forest and SVM</li>
      <li>All trained models saved using <code>pickle</code></li>
      <li>Can make predictions on custom input values</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠️ Technologies Used</h2>
    <ul>
      <li>Python</li>
      <li>Pandas, NumPy</li>
      <li>Matplotlib, Seaborn</li>
      <li>Scikit-learn</li>
      <li>XGBoost</li>
      <li>Pickle</li>
    </ul>
  </div>

  <div class="section">
    <h2>📩 Contact</h2>
    <p>For any queries or contributions, feel free to reach out at:</p>
    <p><strong>Email:</strong> <a href="mailto:sunilr31r@gmail.com">sunilr31r@gmail.com</a></p>
  </div>

</body>
</html>
