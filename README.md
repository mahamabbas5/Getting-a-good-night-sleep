# 🛌 SleepInc: SleepScope Lifestyle Data Analysis

This project analyzes anonymized sleep and lifestyle data from SleepInc's new sleep tracking app, **SleepScope**, to uncover patterns between lifestyle factors and sleep quality.

## 📁 Dataset

The dataset, `sleep_health_data.csv`, includes sleep and health information for **374 individuals** over a 6-month period. It contains 13 columns such as:

- **Gender, Age, Occupation**
- **Sleep Duration**, **Quality of Sleep**, **Sleep Disorder**
- **Physical Activity**, **Stress Level**, **BMI Category**
- **Heart Rate**, **Blood Pressure**, **Daily Steps**

## 🎯 Goals

The aim of this analysis is to help SleepInc:
- Identify occupations with the lowest sleep duration and quality.
- Explore the relationship between **gender**, **physical activity**, and **sleep quality**.
- Examine how **BMI categories** relate to **insomnia rates**.
- Visualize trends for better business and health insights.

## 🔍 Key Insights

- Which occupation has the **lowest average sleep duration**?
- Which occupation has the **lowest sleep quality**?
- Are they the **same occupation**?
- What proportion of each **BMI category** reports **Insomnia**?

## 📊 Visualizations

This project includes visualizations built with **Matplotlib** and **Seaborn** to explore:
- Sleep Quality by Occupation
- Sleep Duration by Gender
- Physical Activity vs. Sleep Quality
- Stress Level vs. Sleep Quality
- BMI Category vs. Insomnia Rates

## 🛠️ Setup

1. Install required libraries:
    ```bash
    pip install pandas matplotlib seaborn
    ```

2. Place `sleep_health_data.csv` in the project directory.

3. Run the analysis:
    ```bash
    python sleep_analysis.py
    ```

   Or explore interactively in Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

## 📂 Files

- `sleep_health_data.csv` — The dataset provided by SleepInc.
- `sleep_analysis.py` — Python script containing the analysis.
- `README.md` — You're reading it!

## 📈 Future Work

- Build predictive models to identify individuals at risk of sleep disorders.
- Include more lifestyle factors like diet, caffeine, or screen time.
- Make the report interactive with Plotly or Streamlit.

---

