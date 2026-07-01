# Customer-Sentiment
Project Summary
The IMDb Movie Reviews dataset contains 50,000 labeled reviews (positive/negative).
analysis focuses on:

Understanding dataset structure

Cleaning and preparing data

Exploring sentiment distribution

Visualizing patterns in review text

Summarizing insights in a polished PDF report

The notebook is fully commented to make the workflow easy to follow.

📂 Repository Contents
IMDB_Analysis.ipynb

IMDB Dataset.csv 

README.md — Project documentation

▶️ How to Run the Notebook
Open IMDB_Analysis.ipynb in Google Colab

Upload the dataset if prompted

Run each cell in order (the notebook includes clear explanations)

Export PDF report via:
File → Print → Save as PDF

If you encounter a missing‑file error, upload the dataset manually:

python
from google.colab import files
files.upload()
Then load it:

python
df = pd.read_csv('IMDB Dataset.csv')
📊 Visualizations Included
Sentiment distribution bar chart

Review length histogram

Sample tables of cleaned data

These visuals help communicate insights quickly 

🛠️ Tools & Technologies
Python

Pandas

Matplotlib

Google Colab

GitHub
