# ac-recommender-system
An intelligent content-based air conditioner recommender system using Flipkart data, powered by user preferences such as budget, room size, and brand. Includes filtering, scoring, and Gradio-based UI for interactive deployment.

# 🧊 AC Recommender System

A content-based recommendation system built using Flipkart air conditioner data. It recommends the most relevant ACs based on user preferences like budget, room size, and brand.

---

## 🚀 Features

- Cleaned and preprocessed Flipkart product dataset
- Intelligent scoring based on:
  - Ratings
  - Discount
  - Energy efficiency
- Custom filtering based on user inputs
- Content-based recommendation logic
- Deployed with **Gradio** for interactive UI

---

## 📂 Dataset

The dataset includes information such as:
- Product name
- Brand
- Ratings and number of reviews
- Final price, MRP, and discount
- Power consumption
- Recommended room size
- Product features

---

## 📦 Requirements

Install the dependencies using:
pip install -r requirements.txt

How to Run
python ac_recommender.ipynb


🌐 Deployment
This project uses Gradio to create an easy-to-use web interface where users can input their preferences and receive personalized AC recommendations.

🧠 Recommender Logic
The recommender ranks ACs using a weighted score based on:

Normalized Rating (40%)
Normalized Discount (30%)
Normalized Efficiency (30%)

👩‍💻 Author
Tamanna Aggarwal
20 years old | Interested in machine learning & recommender systems
GitHub: [metamanna]
Email: [tamanna08aggarwal@gmail.com]
