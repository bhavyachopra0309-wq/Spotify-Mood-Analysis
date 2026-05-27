# Spotify-Mood-Analysis
# 🎧 Can Your Spotify Predict Your Mood?

## 📌 Project Overview

This project is a data analytics project based on Spotify songs.  
The main idea of this project is to analyze music features and classify songs into different moods like:

- 😊 Happy
- 💔 Sad
- 🏋️ Gym
- 🌙 Late Night

I used Python, statistics, probability, and visualization to understand how Spotify song features like energy, valence, danceability, tempo, and popularity can help predict the mood of a song.

The fun idea behind this project is:

> “I used statistics to figure out why my playlist sounds emotionally unstable.”

---

## 🎯 Objective

The objective of this project is to:

- Analyze Spotify song data
- Clean and prepare the dataset
- Classify songs into mood categories
- Find patterns between music features
- Use probability to understand mood distribution
- Perform statistical testing
- Create visualizations for better storytelling

---

## 📂 Dataset

The dataset used in this project contains Spotify song details such as:

- Track name
- Artist name
- Track popularity
- Playlist genre
- Danceability
- Energy
- Valence
- Tempo
- Acousticness

The dataset was uploaded as a ZIP file in Google Colab and extracted using Python.

---

## 🧠 What is Valence?

In Spotify audio features, **valence** means the musical positiveness of a song.

- High valence → happy, cheerful, positive songs
- Low valence → sad, emotional, serious songs

So in this project, valence and energy are used together to predict mood.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Excel
- GitHub

---

## 📚 Concepts Used

This project includes important data analytics concepts:

- Data cleaning
- Data preprocessing
- Exploratory Data Analysis
- Probability
- Correlation analysis
- Hypothesis testing
- Data visualization
- Mood classification
- Basic recommendation system

---

## 📁 Project Structure

```text
spotify-mood-analysis/
│
├── data/
│   └── spotify_songs.csv
│
├── visuals/
│   ├── mood_distribution.png
│   ├── correlation_heatmap.png
│   └── energy_vs_valence.png
│
├── spotify_mood_analysis.ipynb
├── spotify_mood_cleaned.csv
├── README.md
└── requirements.txt
```

---

## 🔍 Mood Classification Logic

The songs are classified based on energy, valence, and tempo.

```python
if valence >= 0.60 and energy >= 0.60:
    mood = "Happy"

elif valence < 0.40 and energy < 0.50:
    mood = "Sad"

elif energy >= 0.75 and tempo >= 110:
    mood = "Gym"

else:
    mood = "Late Night"
```

---

## 📊 Visualizations Included

### 1. Mood Distribution

This graph shows how many songs belong to each mood category.

Example moods:

- Happy
- Sad
- Gym
- Late Night

---

### 2. Correlation Heatmap

The heatmap shows the relationship between features like:

- Energy
- Valence
- Danceability
- Tempo
- Popularity
- Acousticness

This helps in understanding which features are strongly or weakly related.

---

### 3. Energy vs Valence Scatter Plot

This plot shows how songs are spread based on their energy and valence values.

It helps in visually understanding why some songs feel happy, sad, energetic, or calm.

---

## 📈 Probability Analysis

In this project, probability is used to calculate the chance of a song belonging to a particular mood.

Example:

```python
Probability of Happy song = Number of Happy songs / Total number of songs
```

The project calculates probability for:

- Happy songs
- Sad songs
- Gym songs
- Late Night songs

---

## 📉 Correlation Analysis

Correlation is used to check the relationship between energy and valence.

Example question:

> Do high-energy songs also have higher valence?

The project calculates:

- Correlation value
- P-value

If the p-value is less than 0.05, the relationship is considered statistically significant.

---

## 🧪 Hypothesis Testing

This project also uses hypothesis testing to compare Happy songs and Sad songs.

### Null Hypothesis

There is no difference between the average energy levels of Happy songs and Sad songs.

### Alternative Hypothesis

There is a difference between the average energy levels of Happy songs and Sad songs.

A t-test is performed to check if the difference is statistically significant.

---

## 🎵 Song Recommendation Feature

The project also includes a simple mood-based recommendation system.

The user can enter a mood:

```text
Happy
Sad
Gym
Late Night
```

Then the program recommends songs from that mood category.

---

## 🚀 How to Run This Project

### Step 1: Open Google Colab

Go to Google Colab and create a new notebook.

### Step 2: Upload the Dataset

Upload the ZIP file containing the Spotify dataset.

### Step 3: Run the Notebook

Run all cells one by one.

### Step 4: Enter Your Mood

When the program asks:

```text
Enter your mood: Happy, Sad, Gym, or Late Night
```

Type any one mood and get song recommendations.

---

## 📦 Required Libraries

Install these libraries if needed:

```python
pip install pandas matplotlib seaborn scipy
```

---

## 📌 Key Insights

Some insights from this project:

- Songs with high energy and high valence are usually classified as Happy.
- Songs with low energy and low valence are usually classified as Sad.
- High-energy and fast-tempo songs are suitable for Gym mood.
- Many songs fall into the Late Night category because they have mixed emotional features.
- Energy and valence can help in understanding the emotional feel of music.

---

## 💡 What I Learned

Through this project, I learned:

- How to work with real-world music data
- How to clean and analyze a dataset
- How to use probability in data analytics
- How to perform correlation analysis
- How to apply hypothesis testing
- How to create meaningful visualizations
- How to present a data project on GitHub

---

## 🔮 Future Improvements

In the future, this project can be improved by:

- Connecting directly with Spotify API
- Taking user playlist data automatically
- Adding machine learning models
- Creating a web app using Streamlit
- Adding more mood categories
- Making an interactive dashboard using Python

---

## 📸 Instagram Caption Idea

I used Python and statistics to analyze Spotify songs and predict their mood 🎧📊

This project classifies songs into:
😊 Happy  
💔 Sad  
🏋️ Gym  
🌙 Late Night  

Turns out my playlist is not random, it is just statistically chaotic.

---

## 🏷️ GitHub Topics

```text
python
data-analysis
spotify
statistics
probability
data-visualization
pandas
matplotlib
seaborn
google-colab
```

---

Dataset:
https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs


## 👩‍💻 Author

**Bhavya Chopra **

Data Analytics Student  
Learning Python, Statistics, Probability, Excel, and Data Visualization

---

## ⭐ Project Tagline

> Can your playlist reveal your mood?  
> This project tries to find out using data.
