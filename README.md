# 🇦🇺 Australia Wildfire Interactive Dashboard

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Dash](https://img.shields.io/badge/dash-008DE4?style=for-the-badge&logo=dash&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

An advanced, interactive data visualization web application built with **Python**, **Dash**, and **Plotly**. This project analyzes historical wildfire data in Australia, providing real-time insights into fire patterns, affected areas, and vegetation impact.

---

## 🚀 Key Features

* **🔍 Dynamic Data Filtering:** Users can filter over **26,000+ records** of wildfire data by Region and Year seamlessly.
* **📊 Interactive Visualizations:**
    * **Pie Chart:** Displays the Monthly Average Estimated Fire Area, allowing users to see the proportional impact per month.
    * **Bar Chart:** Visualizes the Monthly Average Count of Pixels for Presumed Vegetation Fires.
* **⚡ Reactive Backend:** Built using **Dash Callbacks** to ensure seamless, real-time updates of all visual components without reloading the page.
* **📂 Clean Architecture:** Professional separation of concerns with dedicated files for dependencies, environment settings, and optimized data processing using **Pandas**.

---

## 📸 Dashboard Preview
<img width="1920" height="981" alt="dashboard_preview" src="https://github.com/user-attachments/assets/d8729015-92c0-412d-9897-a901448f882d" />

---

## 🛠️ Tech Stack & Tools
- **Core Language:** Python 3.10+
- **Data Manipulation:** [Pandas](https://pandas.pydata.org/) (Data Cleaning, Grouping, and Aggregation)
- **Dashboard Framework:** [Dash by Plotly](https://dash.plotly.com/) (Web interface and Callbacks)
- **Data Visualization:** [Plotly Express](https://plotly.com/python/plotly-express/)
- **Environment Management:** Virtualenv (Venv)

---

## 📁 Project Structure
```text
Australia-Wildfire-Dashboard/
├── app.py                   # Main application logic and layout
├── Historical_Wildfires.csv  # Cleaned dataset (26k+ fire events)
├── requirements.txt         # List of Python dependencies
├── .gitignore               # Ensures virtual environments are not tracked
└── README.md                # Project documentation and guide
⚙️ Installation & Getting Started
1.Clone the repository

  git clone [https://github.com/MohamedAshraf2710/Australia-Wildfire-Dashboard.git]
  (https://github.com/MohamedAshraf2710/Australia-Wildfire-Dashboard.git)
  cd Australia-Wildfire-Dashboard

2.Set up a Virtual Environment
  python -m venv myenv
  # On Windows:
  myenv\Scripts\activate

3.Install Dependencies
  pip install -r requirements.txt

4.Run the Application
  python app.py
  Open your browser and visit http://127.0.0.1:8050/ to explore the dashboard.

**Developed by Mohamed Ashraf AI Engineer | Backend Developer**
LinkedIn:https://www.linkedin.com/in/mohamed-ashraf-shaaban/
