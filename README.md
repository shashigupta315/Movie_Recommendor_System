# 🎬 Movie Recommendor System

This project is a **Movie Recommender System** built using Python and Machine Learning techniques.  
It suggests movies similar to the one you like based on content-based filtering.

---

## 🚀 Features

- Recommend similar movies based on a selected movie
- Uses **cosine similarity** for finding similar movies
- Built with **scikit-learn**, **pandas**, and **pickle**
- Lightweight: stores preprocessed data inside a similarity.zip file

---

## 📁 Project Structure

- app.py : Main Flask application (or your main Python file)
- similarity.zip : Compressed similarity matrix (176MB)
- templates/ : HTML templates (if any)
- static/ : CSS, images, etc.
- README.md : Project documentation
- requirements.txt : Python dependencies (optional)

---

## ⚙️ How to Run Locally

1. Clone the repository:  
   git clone https://github.com/shashigupta315/Movie_Recommendor_System_.git

2. Extract similarity.zip inside the project folder.

3. Install dependencies:  
   pip install -r requirements.txt

4. Run the application:  
   python app.py

5. Open your browser and go to http://127.0.0.1:5000/

---

## 🛠 Tech Stack

- Python
- Flask (if used)
- scikit-learn
- pandas
- pickle

---

## 📌 Notes

- similarity.pkl was compressed to similarity.zip to avoid GitHub's file size limit.
- Make sure to unzip similarity.zip before running the project.

---

## 🙏 Acknowledgements

Inspired by popular movie recommender systems.

---

## ✨ Author

- Shashi Kr Gupta  
  GitHub: https://github.com/shashigupta315

