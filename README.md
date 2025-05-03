# 🌾 HarvestSense

**HarvestSense** is a machine learning-powered web application designed to predict agricultural crop yields based on regional and environmental features. It helps farmers, researchers, and policymakers make informed decisions for sustainable agriculture.

---

## 🚀 Features

- 🧠 Trained Decision Tree Regressor model
- 📊 Preprocessing pipeline for consistent input
- 🌐 Flask-based web interface
- 📁 Organized and ready-to-deploy code structure

---

## 🗂 Project Structure

├── app.py # Flask web application
├── CropYield-Prediction.ipynb # Jupyter notebook for model development
├── dtr.pkl # Trained Decision Tree model
├── preprocessor.pkl # Saved preprocessing pipeline
├── yield_df.csv # Input dataset
├── requirements.txt # Python dependencies
├── static/
│ └── style.css # Custom CSS styles
├── templates/
│ ├── index.html # Input form UI
│ └── result.html # Output display (optional)
└── README.md # Project documentation

---

## 💻 Setup Instructions

1. Clone the repository:
        git clone https://github.com/yourusername/HarvestSense.git
        cd HarvestSense
2. Install dependencies:
        pip install -r requirements.txt
3. Run the Flask app:
        python app.py
4. Visit the app at:
        http://127.0.0.1:5000

🔮 Future Improvements
🌦️ Integrate real-time weather data APIs

🌱 Expand to more crop types

☁️ Deploy to cloud platforms like Heroku or Render

🤝 Contribution

Feel free to fork the repo, open issues, or submit pull requests. All constructive collaboration is welcome!