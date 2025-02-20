# 🎵 Music Recommendation System 🎶  

## 📌 Project Overview  
This **Music Recommendation System** is built using **Spotify's Million Song Dataset**. The system recommends songs based on lyrics similarity using **TF-IDF vectorization** and **Cosine Similarity**. Users can input a song, and the system will suggest similar tracks.  

## 📂 Dataset Used  
- **Spotify’s Million Song Dataset (Sample: 5000 Songs)**  
- Dataset contains **Artist Name, Song Name, and Lyrics**  

### 🔹 **Data Preprocessing**  
- **Null Values Handled:** Removed missing lyrics and irrelevant data.  
- **Text Processing:**  
  - Lowercased text  
  - Tokenization using **NLTK’s Porter Stemmer**  
  - TF-IDF Vectorization for feature extraction  

---

## 🛠️ Technologies & Libraries Used  
- **Programming Language:** Python  
- **Libraries:**  
  - **Data Handling:** Pandas, NumPy  
  - **Text Processing:** NLTK, Scikit-Learn (TF-IDF Vectorizer)  
  - **Similarity Computation:** Cosine Similarity  
  - **Visualization:** Matplotlib, Seaborn  
- **Deployment:** Streamlit  

---

## 🔍 How It Works  
1. Users **input a song name**.  
2. The system finds similar songs based on **lyrics similarity**.  
3. The recommended songs are displayed with their **artist names**.  

---

## 📊 Machine Learning Model  
The recommendation system is **content-based**, using:  
✔ **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert song lyrics into numerical vectors.  
✔ **Cosine Similarity** to find songs with the closest match.  

---

## 🚀 Deployment  
The project is deployed using **Streamlit**. Run it locally using:  
```bash
streamlit run app.py
