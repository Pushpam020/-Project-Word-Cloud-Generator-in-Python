📌 Word Cloud Generator in Python

Word Cloud Generator in Python is a project that demonstrates how to create visual word clouds from a dataset of movie reviews.
A word cloud is a graphical representation of text data where the size of each word reflects its frequency or importance.

🔹 Libraries Used
pandas → Load and manipulate the dataset
re → Clean text using regular expressions
wordcloud → Generate word clouds
matplotlib.pyplot → Display word cloud plots

🔹 Installation
Make sure you have Python installed (>=3.8). Install the required libraries with:

pip install pandas matplotlib wordcloud

(re is built into Python, no installation required ✅)

🔹 Dataset
This project uses the IMDB Dataset.csv, which contains movie reviews.
"C:\Users\kumar\Downloads\IMDB Dataset.csv\IMDB Dataset.csv"

🔹 Usage
Run the Python script:

python wordcloud_generator.py

🔹 Workflow

Load Data → Import the IMDB dataset into a pandas DataFrame.
Explore Data → Preview column names and sample reviews.
Combine & Clean Text → Merge all reviews, remove unwanted characters, and convert to lowercase.
Remove Stopwords → Exclude common English stopwords for better insights.
Generate Word Cloud → Create word clouds with custom size, colors, and background.
Display Results → Plot and visualize the word cloud using matplotlib.

🔹 Example Output

Below is an example of the generated word cloud:
<img width="790" height="427" alt="image" src="https://github.com/user-attachments/assets/3e9243ea-c5cc-4c3e-ac45-f177b422dba2" />


🔹 Use Cases

Text analysis and visualization
Sentiment analysis of reviews
NLP & data science reports
Creative word-based art
