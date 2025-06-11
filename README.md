# 📊 Tourism Behavior Analysis with Python

A comprehensive exploratory data analysis (EDA) project using **Python**, **Pandas**, **Seaborn**, and **Matplotlib** to uncover insights from a tourism dataset. This project visualizes visitor behavior patterns, spending habits, and travel preferences to support data-driven decisions in the tourism industry.



---

## 📌 Project Objectives

- Analyze tourist demographics and travel patterns  
- Understand spending behavior across countries and categories  
- Visualize destination preferences and age-group trends  
- Compare metrics by travel purposes (e.g., business, leisure, family)  
- Identify key insights for tourism planning and marketing strategies  

---

## 🛠️ Technologies Used

| Tool/Library     | Purpose                        |
|------------------|--------------------------------|
| `pandas`         | Data wrangling and preprocessing |
| `matplotlib`     | Static plotting                 |
| `seaborn`        | Statistical data visualization |
| `numpy`          | Numerical operations            |
| `Excel`          | Data source format              |

---

## 📊 Key Analyses & Visualizations

### 1. 📈 Visitor Demographics  
- **Age Distribution:** Histogram of tourist ages  
- **Gender Distribution:** Pie chart of male vs. female travelers  
- **Travel Purpose:** Bar chart by category (e.g., leisure, business)  

### 2. 💸 Spending Analysis  
- **Average Spending per Category:** Accommodation, transport, food  
- **Top 10 Spending Countries:** Based on total spending  
- **Spending vs Stay Duration:** Scatter plot correlation  

### 3. 🌍 Destination Analysis  
- **Top Preferred Destinations:** Bar chart  
- **Heatmap:** Age group vs. travel purpose  
- **Age Groups:** Segmented into 18–25, 26–35, 36–50, 50+  

### 4. ✈️ Travel Patterns  
- **Stay Duration Distribution:** Boxplot  
- **Travel Frequency Distribution:** Boxplot  
- **Solo vs Family Travel:** Bar chart  

### 5. 📊 Summary Stats by Travel Purpose  
Multi-metric comparison using subplots:  
- Tourist Count  
- Average Age  
- Average Stay Duration  
- Average Spending  
- Travel Frequency  

### 6. 💰 Average Daily Cost (AED)  
- Bar plot comparing **mean**, **min**, and **max** daily costs by travel purpose  

---

## 🧾 Dataset Overview

- Format: `.xlsx`  
- Sample Columns:
  - `Age`, `Gender`, `Country`, `Travel_Purpose`
  - `Stay_Duration_Days`, `Spending_USD`
  - `Average_Spending_Food_USD`, `Average_Spending_Accommodation_USD`
  - `With_Family`, `Preferred_Destination`, `Travel_Frequency_per_Year`

---

## 🚀 How to Run

1. Install required libraries:

2. pip install pandas matplotlib seaborn openpyxl


3. Load the dataset:
Ensure the file tourism_behavior_analysis_updated_data.xlsx is in the working directory.

4. Run the script in any Python IDE or Jupyter Notebook.
All charts will be rendered inline.


📌 Insights Gained
Younger travelers prefer leisure while older age groups lean toward business travel.

Spending increases proportionally with stay duration.

Certain destinations are consistently preferred by family travelers.

Accommodation accounts for the highest share of expenses.

📸 Visual Outputs

![image](https://github.com/user-attachments/assets/59812745-fef0-436f-b619-9e9c7657b923)

![image](https://github.com/user-attachments/assets/f1812bc5-254a-4697-8485-d5b99fa97713)

![image](https://github.com/user-attachments/assets/20a9ee53-8843-47d2-ab31-4c2237912d55)




💡 Future Improvements
Add interactive dashboards using Plotly or Dash

Integrate real-time tourism data APIs

Apply clustering to identify traveler personas

Build predictive models for spending estimation

📝 License
This project is open-source and available under the MIT License.

Made with 🐍 Python & 💙 Data

---

## 👤 Author  
**Name:** Dheeraj Pathak
