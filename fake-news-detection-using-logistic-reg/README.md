<h1 align="center">📰 Fake News Detection using Machine Learning</h1>

<p align="center">
A Machine Learning-based Fake News Detection System built with Python, Scikit-learn, and NLP techniques to classify news headlines as <b>Real</b> or <b>Fake</b>.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
The objective of this project is to develop a machine learning model capable of identifying whether a news headline is genuine or fake. The model is trained using a dataset related to news articles from the Syrian conflict and utilizes Natural Language Processing (NLP) techniques for text preprocessing and feature extraction.
</p>

<p>
The project follows a complete machine learning workflow including:
</p>

<ul>
<li>Data Collection</li>
<li>Data Preprocessing</li>
<li>Text Cleaning</li>
<li>Stemming</li>
<li>TF-IDF Feature Extraction</li>
<li>Model Training</li>
<li>Model Evaluation</li>
<li>Prediction System</li>
<li>Interactive Google Colab GUI</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
<li>News headline classification</li>
<li>Text preprocessing using NLP</li>
<li>Stopword removal</li>
<li>Word stemming using Porter Stemmer</li>
<li>TF-IDF vectorization</li>
<li>Logistic Regression classifier</li>
<li>Training and testing accuracy evaluation</li>
<li>Interactive GUI in Google Colab</li>
<li>User-friendly headline prediction interface</li>
</ul>

<hr>

<h2>🛠 Technologies Used</h2>

<table>
<tr>
<th>Technology</th>
<th>Purpose</th>
</tr>

<tr>
<td>Python</td>
<td>Programming Language</td>
</tr>

<tr>
<td>Pandas</td>
<td>Data Manipulation</td>
</tr>

<tr>
<td>NumPy</td>
<td>Numerical Operations</td>
</tr>

<tr>
<td>NLTK</td>
<td>Natural Language Processing</td>
</tr>

<tr>
<td>Scikit-Learn</td>
<td>Machine Learning Algorithms</td>
</tr>

<tr>
<td>KaggleHub</td>
<td>Dataset Downloading</td>
</tr>

<tr>
<td>ipywidgets</td>
<td>Interactive GUI Components</td>
</tr>

<tr>
<td>Google Colab</td>
<td>Development Environment</td>
</tr>

</table>

<hr>

<h2>📂 Dataset</h2>

<p>
Dataset used in this project:
</p>

<p>
<b>A Fake News Dataset Around the Syrian War</b>
</p>

<p>
Available on Kaggle:
</p>

<a href="https://www.kaggle.com/datasets/mohamadalhasan/a-fake-news-dataset-around-the-syrian-war">
https://www.kaggle.com/datasets/mohamadalhasan/a-fake-news-dataset-around-the-syrian-war
</a>

<br><br>

<p>
The dataset contains information such as:
</p>

<ul>
<li>News Source</li>
<li>Article Title</li>
<li>Labels</li>
</ul>

<hr>

<h2>⚙️ Machine Learning Pipeline</h2>

<h3>1. Data Collection</h3>

<p>
Dataset downloaded using KaggleHub.
</p>


<h3>2. Data Preprocessing</h3>

<ul>
<li>Handling missing values</li>
<li>Merging source and article title</li>
<li>Removing special characters</li>
<li>Converting text to lowercase</li>
<li>Removing stopwords</li>
<li>Applying stemming</li>
</ul>


<h3>3. Feature Extraction</h3>

<p>
TF-IDF Vectorizer is used to transform textual data into numerical feature vectors.
</p>


<h3>4. Model Training</h3>

<p>
Algorithm Used:
</p>

<pre>
Logistic Regression
</pre>


<h3>5. Model Evaluation</h3>

<p>
Evaluation Metric:
</p>

<ul>
<li>Accuracy Score</li>
</ul>


<h3>6. Prediction System</h3>

<p>
Users can input a news headline and receive an instant prediction indicating whether the news is real or fake.
</p>

<hr>

<h2>🖥 Interactive Google Colab GUI</h2>

<p>
The project includes a simple GUI built using <b>ipywidgets</b> in Google Colab.
</p>

<p>
Features:
</p>

<ul>

<li>Source Input Field</li>

<li>Headline Input Text Area</li>

<li>Prediction Button</li>

<li>Real/Fake Result Display</li>

</ul>

<hr>

<h2>📈 Model Performance</h2>

<p>
The model performance depends on the train-test split and dataset distribution.
</p>

<p>
Metrics obtained:
</p>

<pre>
Training Accuracy : 78.42%

Testing Accuracy  : 58.02%
</pre>


<hr>

<h2>▶️ Installation</h2>

<pre>
git clone https://github.com/Maitri0904/Fake-News-Detection.git

cd Fake-News-Detection
</pre>

<p>Install dependencies:</p>

<pre>
pip install numpy

pip install pandas

pip install nltk

pip install scikit-learn

pip install kagglehub

pip install ipywidgets
</pre>

<hr>

<h2>▶️ Run the Project</h2>

<p>
Open the notebook in Google Colab and execute all cells sequentially.
</p>

<p>
After training completes, use the GUI to enter:
</p>

<ul>

<li>News Source</li>

<li>Headline</li>

</ul>

<p>
Click the <b>Check News</b> button to obtain predictions.
</p>

<hr>

<h2>📌 Limitations</h2>

<ul>

<li>The model is trained on a Syrian-war-specific dataset.</li>

<li>Predictions for unseen domains such as NDTV, BBC, Reuters, or CNN may not always be accurate.</li>

<li>The model uses TF-IDF and Logistic Regression, which may have limitations in understanding contextual semantics.</li>

</ul>

<hr>

<h2>🔮 Future Improvements</h2>

<ul>

<li>Train on larger and more diverse datasets.</li>

<li>Integrate real-time news feeds.</li>

<li>Deploy as a Flask or Streamlit web application.</li>

<li>Use transformer-based models such as BERT or RoBERTa.</li>

<li>Improve cross-domain generalization.</li>

</ul>

<hr>

<h2>👨‍💻 Author</h2>

<p>
<b>Maitri Chopda</b>
</p>

<p>
Machine Learning Enthusiast | Python Developer
</p>

<p>
GitHub:
<a href="https://github.com/yourusername">
https://github.com/Maitri0904
</a>
</p>

<hr>

<h2 align="center">⭐ If you found this project useful, consider giving it a star on GitHub.</h2>
