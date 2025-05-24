# 🌍 Food Prices Analyzer
Food Prices Analyzer is a full-stack web application that visualizes global food price trends based on imports, exports, temperature, and climate factors. Built with React and Flask, it offers interactive charts to explore commodity and country-wise pricing patterns. The platform uses datasets from sources like Kaggle to uncover key insights in food prices.

---

## ✨ Key Features

- 📈 **Trend Analysis**: Visualize historical price fluctuations for various food commodities.
- 🌍 **Global Comparison**: Analyze food import/export trends across countries and regions.
- 🎯 **Dynamic Filtering**: Filter data by category (e.g., grains, vegetables, meats) and time period.
- 📱 **Responsive UI**: Built with modern React components and Bootstrap for mobile-friendly design.
- ⚙️ **Flask API**: Efficient data processing and backend logic using Python and Pandas.

## Tech Stack

| Layer      | Technologies Used                     |
|------------|----------------------------------------|
| Frontend   | React.js, HTML5, CSS3, Bootstrap       |
| Backend    | Python, Flask, Pandas                  |
| Dev Tools  | Node.js, Virtualenv, Git, VS Code      |

---

## Project Structure
```
Food-Prices-Analyzer/
├── Flask/                   # Flask backend and virtual environment
│   ├── FlaskEnv/            # Virtual environment
│   └── app.py               # Main backend logic
│
├── ReactApp/                # React frontend application
│   ├── public/
│   └── src/
│       └── components/      # Modular React components
│
├── datasets/                # Cleaned CSV files for analysis
└── README.md
````

##  Getting Started

### Backend Setup (Flask)

```bash
cd Flask
python3 -m venv FlaskEnv
source FlaskEnv/bin/activate  # or FlaskEnv\Scripts\activate on Windows
pip install -r requirements.txt
python app.py
````

### Frontend Setup (React)

```
cd ReactApp
npm install
npm start
````

By default:

* Frontend runs at: `http://localhost:3000`
* Backend runs at: `http://localhost:5000`

