<h1 align="center">🎬 Movie Recommender System</h1>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg" />
  <a href="https://github.com/mdafzal786-dev/Movie-Recommender-System" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
</p>

> A Streamlit-based Movie Recommender System that suggests movies similar to a selected movie using a precomputed similarity matrix. The app allows users to interactively select movies and receive recommendations.

---

## 🏠 Demo
*(Replace this with live Streamlit demo URL if hosted)*
[Live Demo](#)

---

## 💻 Tech Stack
- **Python** – Core programming language
- **Streamlit** – Web interface
- **Pandas** – Data handling
- **Pickle** – Load serialized data (movies & similarity matrix)
- *(Optional)* **Requests** – Fetch movie posters from TMDB API
- *(Optional)* **TMDB API** – For movie poster images

---

## 🛠 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/mdafzal786-dev/Movie-Recommender-System.git
cd Movie-Recommender-System

Install dependencies
pip install streamlit pandas
# Optional for poster images
pip install requests

▶️ Usage
streamlit run app.py
