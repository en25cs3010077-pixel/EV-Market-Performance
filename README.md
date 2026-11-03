# ⚡ EV Market Performance Dashboard

An interactive web-based project that explores and presents Electric Vehicle (EV) market performance through data visualizations and insights.

🌐 **Live Website:** [EV Market Performance](https://ev-market-performance-d7bw.onrender.com)

📂 **GitHub Repository:** [EV Market Performance](https://github.com/en25cs3010077-pixel/EV-Market-Performance)

---

## 📌 Project Overview

The **EV Market Performance Dashboard** is designed to provide an overview of the electric vehicle market using data-driven visualizations and analysis.

The project combines a Flask-based web application with interactive Tableau dashboards to make EV market information easier to explore and understand.

It provides a centralized platform for viewing market trends, exploring visual insights, and understanding the growth and development of the electric vehicle industry.

## 🎯 Objectives

- Explore electric vehicle market performance.
- Present EV-related data through interactive visualizations.
- Identify market trends and patterns.
- Make data insights accessible through a simple web interface.
- Integrate Tableau dashboards into a Flask web application.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend development |
| Flask | Web application framework |
| HTML5 | Page structure |
| CSS3 | Styling and layout |
| Tableau | Data visualization and dashboards |
| Gunicorn | Production WSGI server |
| Render | Cloud hosting and deployment |
| Git & GitHub | Version control and source code management |

## ✨ Features

- Responsive web interface.
- EV market performance overview.
- Interactive Tableau dashboard integration.
- Data story and visualization links.
- About section describing the project.
- Cloud deployment using Render.

## 📁 Project Structure

```text
EV-Market-Performance/
│
├── app.py                 # Flask application
├── requirements.txt       # Python dependencies
├── Procfile               # Production start configuration
├── README.md              # Project documentation
├── .gitignore             # Files excluded from Git
│
├── static/
│   └── style.css          # Website styles
│
└── templates/
    └── index.html         # Main webpage
```

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/en25cs3010077-pixel/EV-Market-Performance.git
```

### 2. Navigate to the project folder

```bash
cd EV-Market-Performance
```

### 3. Create a virtual environment

```bash
python3 -m venv venv
```

### 4. Activate the virtual environment

**macOS / Linux:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Start the Flask application

```bash
python app.py
```

Open your browser and visit:

```text
http://127.0.0.1:5000
```

## ☁️ Deployment

The application is deployed on **Render** using Gunicorn.

**Build Command:**

```bash
pip install -r requirements.txt
```

**Start Command:**

```bash
gunicorn --bind 0.0.0.0:$PORT app:app
```

**Live Application:**  
https://ev-market-performance-d7bw.onrender.com

## 📊 Data Visualization

The project integrates Tableau visualizations to present EV market insights interactively.

Use the Dashboard and Data Story sections on the website to explore the visualizations.

## 👨‍💻 Author

**GitHub:** [en25cs3010077-pixel](https://github.com/en25cs3010077-pixel)

## 📄 License

This project is created for educational and learning purposes.

---

⭐ If you find this project interesting, consider starring the repository!
