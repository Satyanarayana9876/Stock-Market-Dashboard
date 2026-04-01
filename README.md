# 📈 Stock Data Intelligence Dashboard

A full-stack financial analytics platform designed to deliver real-time stock insights, interactive visualizations, and **AI-based price forecasting**. This system extends beyond simple data retrieval by incorporating **ensemble machine learning techniques** and **high-performance caching** to provide near institutional-level analytics.

## 🚀 Key Features

### 📊 Advanced Visualization

* **Real-Time Intraday Monitoring:** Enables a “Day Trading” (1D) view with live, minute-level updates.
* **Interactive Historical Analysis:** Provides zoomable charts across multiple timeframes (1M, 1Y, 5Y, MAX) powered by **ApexCharts**.
* **Flexible Chart Modes:** Easily switch between Area, Line, and Candlestick visualizations.
* **Intelligent Data Presentation:** Includes automatic currency formatting (e.g., ₹1,500 Cr) and dynamic color indicators (green/red) based on market movement.

### 🧠 AI & Machine Learning Engine

* **Ensemble Modeling Approach:** Combines **Linear Regression** (for capturing trends) and **Random Forest** (for handling complex, non-linear patterns) to forecast next-day closing prices.
* **Risk Assessment Module:** Calculates stock volatility and categorizes assets into “Stable” or “High Risk” using statistical thresholds.

### ⚡ Performance Optimization

* **Data Downsampling Strategy:** Enhances performance for long-term (MAX) charts by aggregating daily data into weekly intervals, reducing payload size by up to 80% while preserving trend integrity.
* **Fault-Tolerant Backend:** Integrates auto-retry mechanisms to handle external API failures seamlessly, ensuring uninterrupted service.

---

## 🛠️ Tech Stack
| Components | Technologies Used |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Glassmorphism), JavaScript (ES6+), ApexCharts.js |
| **Backend** | Python 3.10+, FastAPI (Asynchronous High-Performance API) |
| **ML & Data** | Pandas, NumPy, Scikit-Learn (RandomForest, LinearRegression) |
| **Persistence** | SQLite3 (Local History Backup) |
| **Data Source** | Yahoo Finance (yfinance) |

---
