# 🚗 Traffic Accident Data Analysis and Visualization

This project analyzes U.S. traffic accident data to identify patterns and contributing factors based on **road conditions**, **weather**, and **time of day**. It also visualizes accident hotspots on a U.S. map.

---

## 📊 Project Objectives

- Analyze how road and weather conditions affect accident severity.
- Identify peak hours and days for traffic accidents.
- Visualize accident hotspots geographically.
- Explore correlations between environmental conditions and severity.

---

## 📁 Dataset

- **Source**: [US Accidents (2016 - 2023)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)  
- **Size**: ~7 million records  
- **Format**: CSV

---

## 🛠️ Tools & Libraries

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Folium (for map visualizations)
- Jupyter Notebook

---

## 📌 Features Extracted

- `Hour`, `Day`, `Month` from `Start_Time`
- Top 10 Weather Conditions
- Visibility and its relation to accident severity
- Correlation matrix of weather-related variables
- Geographic accident heatmap

---

## 📉 Visualizations

- Bar plots (accidents by hour, weather)
- Box plots (visibility vs severity)
- Correlation heatmap
- Interactive geographic heatmap of accident hotspots using Folium

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/traffic-accident-analysis.git
   cd traffic-accident-analysis
````

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook Traffic_Accident_Analysis.ipynb
   ```

4. To view the accident map:

   * Run the notebook cell that saves `accident_hotspots.html`
   * Open that file in your browser

---

## 📌 Folder Structure

```
traffic-accident-analysis/
├── Traffic_Accident_Analysis.ipynb
├── US_Accidents_March23.csv
├── accident_hotspots.html
├── requirements.txt
└── README.md
```

---

## ✅ Future Improvements

* Predictive modeling of accident severity
* Add weekend vs weekday comparison
* Build a Streamlit dashboard

---

## 🧑‍💻 Author

**Y. Narmadha**
MCA Student, SITS Hyderabad
📧 [narmadhayadav33@gmail.com](mailto:narmadhayadav33@gmail.com)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

```
