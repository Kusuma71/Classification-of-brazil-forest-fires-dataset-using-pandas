<div id="top"></div>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

<h3 align="center">Brazil Forest Fire Classification</h3>

  <p align="center">
    A data-driven approach to classify forest fire occurrences in Brazil.
    <br />
    <a href="https://github.com/Kusuma71/Brazil-Forest-Fire-Classification"><strong>View Repository »</strong></a>
  </p>

---

## 🧠 Project Overview

This project was developed by <b>S. Kusuma</b> as part of a Data Science internship to explore the use of Python and machine learning in real-world environmental datasets. The focus was on analyzing and classifying forest fire data from Brazil using Pandas and supervised ML algorithms.  
<br>
The goal was to create a predictive model that can identify potential fire incidents based on historical data, and present it via a simple web interface using Flask.

---

## 🌎 Dataset Overview

The dataset used is the official Brazil forest fire record that contains monthly records of fire incidents across various states and regions. The features include:
- Year, Month, State, Region
- Number of fire points
- Climate zones

---

## 📊 Key Features

<ul>
  <li>Data preprocessing using Pandas</li>
  <li>Visual EDA using Matplotlib and Seaborn</li>
  <li>Correlation analysis between weather and fire frequency</li>
  <li>Classification using Logistic Regression, Random Forest, and XGBoost</li>
  <li>Deployment-ready Flask application</li>
</ul>

---

## ⚙️ Technologies Used

<ul>
  <li><b>Language:</b> Python</li>
  <li><b>Libraries:</b> Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn</li>
  <li><b>ML Models:</b> Logistic Regression, Decision Tree, Random Forest, XGBoost</li>
  <li><b>Web App:</b> Flask</li>
  <li><b>Tools:</b> Git, GitHub, Postman</li>
</ul>

---

## 🪜 Steps Followed

### 📌 Environment Setup
- Installed required tools: Python, Git, MongoDB, and Flask
- Created virtual environment and installed dependencies

### 📌 Data Handling
- Loaded and cleaned the CSV file using Pandas
- Removed inconsistent data and handled missing values
- Performed region-wise fire point aggregation

### 📌 EDA & Visualization
- Used bar plots, line charts, and heatmaps to understand seasonal patterns
- Discovered that certain states have higher fire frequency in dry months

### 📌 Model Building
- Target variable: Fire Incident (`Yes/No`)
- Applied multiple classification models to predict binary fire occurrence
- Split data into training and testing sets
- Evaluated models using accuracy, F1 score, and confusion matrix

### 📌 Web Application (Flask)
- Built a lightweight Flask app for live testing
- Form takes input like region, month, etc., and returns prediction
- API endpoint for model testing via Postman

---

## 🙋‍♀️ Developed By

**S. Kusuma**  
📧 [Priyakusuma724@gmail.com](mailto:Priyakusuma724@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/s-kusuma-122180203)

---

## 📄 License

This project is open-source and free to use under the MIT License.

<p align="right">(<a href="#top">back to top</a>)</p>
