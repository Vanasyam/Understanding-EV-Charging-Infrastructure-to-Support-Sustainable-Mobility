# Understanding-EV-Charging-Infrastructure-to-Support-Sustainable-Mobility – Capstone Project

The aim of this project is to analyze EV charging station data to understand how charging locations, connector types, and station capacity vary across regions.

---

## Project Overview
Electric Vehicle adoption is increasing worldwide, and charging infrastructure plays a major role in supporting sustainable mobility.  
This project analyzes EV charging station data from multiple countries to uncover insights about:

- Where charging stations are located  
- How many connectors stations typically have  
- What types of connectors are most common  
- How infrastructure differs between countries  
- Geographic clustering and distribution patterns  

---

##  Project Objectives
- Load and understand the dataset 
- Clean, sanitize, and prepare the data for analysis 
- Perform univariate, bivariate, and multivariate analysis 
- Summarize key findings and document insights 

---

##  Repository Structure

EV-Charging-Analysis/  
│  
├── Problem Definition & Data Loading.ipynb  
├── Data Cleaning & Pre-processing.ipynb  
├── EDA & Visualizations.ipynb  
├── Final Project.ipynb  
│  
├── data/
│   ├── ev_stations_2025.csv          
│   └── Cleaned.csv   
│ 
└── README.md  

Each notebook corresponds to one task in the project and can be run independently.

---

## Key Insights

- Most EV stations worldwide have **only one connector**, showing that global EV infrastructure is still developing.  
- Charging stations are heavily concentrated in **North America, Europe, and parts of Asia**, with other regions having minimal coverage.  
- **Connector types vary by region**:  
  - Europe → Type 2, CCS  
  - United States → NEMA, CCS  
  - Malaysia → mixed usage  
- Some countries (e.g., Denmark, Malaysia) deploy **higher-capacity stations** with more connectors.  
- The dataset mostly includes stations added in **2025**, making it a snapshot rather than a multi year trend.  
- Geographic location shows **weak correlation** with station capacity.

---

##  Techniques & Tools Used
- **Python (Pandas, NumPy)** – data handling  
- **Matplotlib, Seaborn** – visualizations  
- **Feature engineering** – connector type expansion, date transformation  
- **EDA** – univariate, bivariate, multivariate analysis  
- **Geographical visualization** – latitude/longitude plot  

---

## How to Run This Project

### 1. Clone the Repository
git clone https://github.com/<Vanasyam>/Understanding-EV-Charging-Infrastructure-to-Support-Sustainable-Mobility.git

### 2. Install Dependencies
pip install pandas numpy matplotlib seaborn

### 3. Open the Notebooks
jupyter notebook

### 4. Run the tasks in order:
1. Task 1 – Load data  
2. Task 2 – Cleaning  
3. Task 3 – EDA  
4. Task 4 – Insights  

---

## Author
**Vanasyam Mungath**  
Data Analytics – Entri Elevate  
2025  
