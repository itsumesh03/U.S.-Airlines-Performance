# ✈️ U.S. Airline Performance & Delay Analysis  
**SQL + Power BI Capstone Project**

## 📌 Project Overview
This project analyzes **U.S. domestic flight performance (2015)** to uncover:
- Patterns in **delays** and **cancellations**  
- **Airline and airport performance** benchmarking  
- Time-based and route-based **delay trends**  
- **Actionable recommendations** for operational improvements  

The project integrates **SQL** for data preparation and **Power BI** for visualization.

---

## 📂 Dataset

- **`flights.csv`** – Detailed flight data (year, month, airline, departure/arrival delays, cancellations)  
- **`airlines.csv`** – Airline IATA codes and names  
- **`airports.csv`** – Airport codes, names, locations, lat/lon  

---

## 🛠 Tools & Technologies
- **SQL** – Data ingestion, cleaning, transformation, and exploratory data analysis (EDA)  
- **Power BI** – 4-page interactive dashboard for insights and storytelling  
- *(Optional)* **Excel/Python** – For supplementary analysis or data checks  

---

## 📑 SQL Workflow
**1. Data Cleaning**
- Null handling for delay and time fields  
- Time conversion (HHMM ➡ HH:MM)  
- Created descriptive cancellation reasons  

**2. EDA**
- Delay analysis by **airline**, **airport**, **month**  
- Cancellation reasons distribution  
- Taxi-out and taxi-in time impact  

**3. Integration**
- Joined flights with airlines and airports datasets  
- Created **unified dataset** for Power BI  

---

## 📊 Power BI Dashboard
**Dashboard has 4 pages:**
1. **Overview** – KPIs, delay trends, airport delay map
  <img width="940" height="556" alt="image" src="https://github.com/user-attachments/assets/335757e2-f13b-4dd8-9095-bef3a5e22236" />

2. **Airline Performance** – OTP %, avg delays, cancellation breakdown
    <img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/5a4a4f27-cb83-49cb-a83a-f821b8239ebc" />

3. **Airport & Routes** – Top delay airports, route heatmap
   <img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/0e763d16-7bca-466e-9b70-8f3bf7f76f73" />

4. **Delay Reasons & Forecasting** – Delay type analysis, predictions  
<img width="940" height="528" alt="image" src="https://github.com/user-attachments/assets/8b52efb9-a343-41e2-890b-5a351aa9e75b" />



---

## 🚀 How to Use
1. Clone the repository:
```bash
git clone https://github.com/yourusername/airline-delay-analysis.git
