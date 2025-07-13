# 🎵 **Spotify Song Mood Prediction & Clustering** 🎶

This project explores the fascinating connection between **music features** and **song moods** using data scraped from Spotify's Web API. By analyzing audio characteristics like **danceability**, **energy**, **loudness**, and **valence**, we uncover patterns that can help predict the mood of a song and even cluster songs based on similar features.

👨‍💻 **Group Members**:
- Noor Rehman [Email](mailto:hello.noorrehman@gmail.com)
- Alisha Rubab [Email](mailto:alisharubab7@gmail.com)
- Aliha Fatima

---

## 🚀 **Project Overview**
The goal of this project is to predict **song moods** and perform **clustering analysis** based on Spotify's dataset of 1,000 artists. By examining **audio features** such as **danceability**, **energy**, **loudness**, and **valence**, we aim to build a model that helps in personalizing music recommendations, particularly for **mental health applications**.

🎧 We used Python libraries such as **Pandas**, **NumPy**, **Scikit-learn**, and **Plotly** to carry out data preprocessing, visualization, clustering, and mood prediction. 

---

## 📊 **Step-by-Step Breakdown**

### 1️⃣ **Data Collection**
Using **Spotify's Web API**, we scraped data from 1,000 artists. The collected data includes:
- **Artist Information**: Name, genre, popularity, and follower count.
- **Track Information**: Track name, album name, release date, and audio features such as danceability, energy, loudness, and valence.

### 2️⃣ **Data Preprocessing**
After collecting the data, we cleaned and transformed it:
- **Handled Missing Values**: Any missing or incorrect data was appropriately dealt with.
- **Normalization**: Audio features were normalized to ensure that they could be processed effectively for analysis and model building.

### 3️⃣ **Data Visualization**
We used **Plotly** to create interactive visualizations to uncover:
- The **most-followed artists**.
- **Trends in song releases** over the years.
- **Audio features comparison** and their correlation with mood.
- **Tree maps** to show the distribution of artists by genre.

### 4️⃣ **Clustering Analysis**
To analyze mood similarities between songs, we employed **K-means clustering**. The elbow curve was used to determine the optimal number of clusters. This allows us to group songs with similar moods and genres, creating a better understanding of music trends.

### 5️⃣ **Mood Prediction with SVC (Support Vector Classifier)**
We built a **Predictive Model** using **SVC** to classify the mood of a song based on its audio features:
- Features used for classification: **danceability**, **valence**, **tempo**, **loudness**, and **energy**.

The **SVC model** yielded accuracy scores between **83.75% and 93.75%**, indicating that the model is reliable and can predict moods consistently.

---

## 🌍 **SDG Alignment**

### 🎯 **Good Health & Well-Being (SDG 3)**
This project aligns with **SDG 3**, aiming to improve health and well-being. By predicting moods through music, we contribute to:
- **Music Therapy**: Helping improve mental health with music-based interventions.
- **Personalized Wellness**: Providing users with **mood-based playlists** that enhance mental health and well-being.

---

## 🔮 **Future Work & Applications**
- **Music Therapy Apps**: Use mood prediction to design **customized music therapy** playlists.
- **Music Recommendation Systems**: Enhance music recommendations for streaming platforms like Spotify.
- **Mental Health Support**: Incorporate mood prediction models into wellness apps to help manage stress, anxiety, and depression.

---

## 🛠 **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - **Pandas** for data manipulation
  - **NumPy** for numerical operations
  - **Scikit-learn** for clustering and classification
  - **Plotly** for interactive visualizations
- **Spotify Web API** for data scraping

---

## 📈 **Key Results**
- **Mood Prediction Accuracy**: 83.75% - 93.75%
- **Clustering Insights**: Songs grouped by mood and genre.
- **Visualizations**: Dynamic, interactive charts revealing music trends, artist popularity, and audio feature distributions.

---

## 👁 **Conclusion**
By understanding the relationship between music features and moods, this project has opened the door to a new realm of **personalized music experiences**. It also presents exciting opportunities in **mental health** and **well-being**, making music therapy more accessible and impactful. 

---

## 🔗 **Links**
- [Spotify Web API Documentation](https://developer.spotify.com/documentation/web-api/)
- [Research Paper on Music Mood Prediction](https://www.researchgate.net/publication/370450676_Music_Mood_Prediction_Based_on_Spotify's_Audio_Features_Using_Logistic_Regression)
- [SDG 3 - Good Health and Well-Being](https://sdgs.un.org/goals/goal3)

---

## 💬 **How to Contribute**
Feel free to fork this repository and make improvements, whether it’s refining the model, adding new features, or simply improving the visualizations. Contributions are always welcome! 😄

---

📢 **Stay tuned for updates on future features and improvements!**
