# 🌲 ForestIQ
ForestIQ is a full-stack forest monitoring and analysis system that leverages machine learning, computer vision, and geospatial data to estimate green cover, count trees, and identify tree species. The platform is built with a modular architecture combining Python-based AI models, Flask and Express backends, and a React frontend for seamless interaction and visualization.

## 🚀 Key Features

> 🌳 Tree Counting using aerial/satellite imagery

> 🧠 Tree Species Classification with ML/DL models

> 🖼️ Image Preprocessing with OpenCV

> 🔗 Dual Backend System – Python Flask for ML, Node.js Express for APIs

> 🖥️ Frontend built in React for visualizing results and interaction

> 📦 Web-compatible Models for on-device predictions (via web_model/)

## 🛠️ Tech Stack

> Frontend: React.js (in /client), Tailwind CSS, Axios for API communication

> Backends: Flask (for serving ML models), Express.js (for app logic and routing), RESTful APIs

> Machine Learning: Python (OpenCV, NumPy, TensorFlow/PyTorch, scikit-learn), Custom-trained
models for tree detection and classification

> Data Handling: PostgreSQL or MongoDB (if applicable), JSON/CSV for model input-output

## 🔧 Installation

> Clone the repository:
```
git clone https://github.com/ShashankDahake7/ForestIQ.git
cd ForestIQ
```
> Frontend Setup (React)
```
cd client
npm install
npm run dev
```
> Flask Backend (ML Server)
```
cd flask-backend
pip install -r requirements.txt
python app.py
```
> Node.js API Server
```
cd server
npm install
npm start
```

## 📽️ Watch the demo video:

> [![Watch the video](https://www.youtube.com/watch?v=lauP49UdGzI)

## 🚀 Demo

> https://forestiq-frontend.onrender.com/
