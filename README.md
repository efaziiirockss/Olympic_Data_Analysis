# Olympics Data Analysis App

A Streamlit-based web application to explore and visualize historical Olympics data, using pandas, Plotly, seaborn, and matplotlib.

## 📊 Features

* **Medal Tally**: View medal counts by year and country.
* **Overall Analysis**:

  * Top stats like number of editions, sports, athletes, nations.
  * Line charts of athlete, nation, and event growth.
  * Heatmaps showing events per sport over time.
  * List of most successful athletes.
* **Country-wise Analysis**:

  * Medal trends of a country over years.
  * Heatmap of medals across sports.
  * Top 10 athletes from a country.
* **Athlete-wise Analysis**:

  * Distribution of athlete ages.
  * Sport-wise age distribution of gold medalists.
  * Height vs Weight scatterplot.
  * Men vs Women participation over time.

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **pandas**
* **numpy**
* **plotly**
* **seaborn**
* **matplotlib**

## 🗂️ Dataset Used

* `athlete_events.csv`: Main dataset of Olympic athletes.
* `noc_regions.csv`: Region mapping for National Olympic Committees (NOCs).

## 🚀 How to Run

1. Clone the repository or download the files.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run app.py
```

## 📁 Project Structure

```
├── app.py               # Main Streamlit app
├── helper.py            # Functions for data analysis
├── preprocessor.py      # Data cleaning and preprocessing
├── athlete_events.csv   # Olympics athlete data
├── noc_regions.csv      # NOC region mapping
├── README.md
```

## ✅ To Do / Suggestions

* Add filtering by gender or sport in more sections
* Deploy the app via Streamlit Cloud or Render

## 📸 Screenshots

*Add screenshots of the UI here if desired.*

---
