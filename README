# TED Talks Recommendation System 🎤  
**A Machine Learning-Powered Content-Based Recommender**

A content-based recommendation system that suggests TED Talks using **Natural Language Processing (NLP)** and **Machine Learning**.

---

## 🌟 Overview

This project builds a **recommendation engine** for TED Talks using:
- **Text preprocessing** (stopwords removal, punctuation cleaning)
- **TF-IDF Vectorization** to convert talk descriptions into numerical vectors
- **Cosine Similarity** to find talks with similar themes
- Built and tested in **Jupyter Notebook**

🎯 **Goal**: Recommend relevant TED Talks based on user input (e.g., "climate change", "time management").

---

## 📁 Project Structure

```
Recommendation_System/
├── reco.ipynb          ← Jupyter Notebook with full implementation
└── tedx_dataset.csv    ← Dataset of TED Talks (2006–2020)
```

---

## 📊 Dataset

- **Source**: TED Talks (public dataset)
- **Time Range**: 2006 – 2020
- **Features Used**:
  - `title`: Talk title
  - `details`: Talk description and content
  - `main_speaker`: Speaker name
- **Preprocessing**: Cleaned text (removed stopwords, punctuation) for NLP tasks.

---

## ⚙️ How It Works

1. **Input**: User provides a topic of interest (e.g., `"How to be productive"`).
2. **Processing**: The system:
   - Cleans and vectorizes the input using TF-IDF.
   - Computes similarity with all talks using **cosine similarity**.
3. **Output**: Returns the **top 5 most similar TED Talks**.

🔧 **Techniques Used**:
- `TfidfVectorizer` (scikit-learn)
- `cosine_similarity`
- Text cleaning with `nltk` and `string`

---

## 🖼️ Example Output

**Input**:  
`"Climate change and how we can save the planet"`

**Recommended Talks**:
1. **Speaker**: Al Gore  
   **Talk**: On the danger of global warming...
2. **Speaker**: Greta Thunberg  
   **Talk**: The climate crisis is the fight of our lives...

*(Generated in `reco.ipynb`)*

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/Recommendation_System.git
cd Recommendation_System
```

### 2. Install Dependencies
```bash
pip install pandas numpy nltk scikit-learn matplotlib wordcloud jupyter
```

> 💡 Tip: Use a virtual environment:
> ```bash
> python -m venv env
> source env/bin/activate  # On Windows: env\Scripts\activate
> ```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook reco.ipynb
```

### 4. Run All Cells
- The notebook will:
  - Load the dataset
  - Preprocess text
  - Build the recommender
  - Show recommendations

---

## 🧪 Test It Yourself

Try these inputs in the notebook:
```python
talk_content = ['Time management and success']
recommend_talks(talk_content)

talk_content = ['Climate change and sustainability']
recommend_talks(talk_content)
```
