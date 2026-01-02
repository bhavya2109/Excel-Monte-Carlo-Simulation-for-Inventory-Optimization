# Excel Monte Carlo Simulation for Inventory Optimization

## 📌 Project Overview
This project demonstrates the use of Monte Carlo simulation in Microsoft Excel to optimize inventory reorder points under uncertain demand. The model simulates thousands of possible demand scenarios and evaluates stockout risk to support data-driven inventory decisions.

---

## 🎯 Objective
- Model uncertain customer demand using probability distributions  
- Run a Monte Carlo simulation with 10,000 iterations in Excel  
- Analyze stockout probability at different reorder points  
- Identify an optimal reorder point that balances service level and inventory risk  

---

## 🛠 Tools & Technologies
- Microsoft Excel  
- Excel Functions: RAND(), NORMINV(), AVERAGE(), STDEV()  
- What-If Analysis (Data Table)  
- CSV dataset for historical demand  

---

## 📂 Dataset
The dataset (`inventory_data.csv`) contains historical demand information used to estimate:
- Average demand  
- Demand variability (standard deviation)  

This data forms the basis for random demand generation in the simulation.

---

## ⚙️ Methodology
1. Calculated average demand and standard deviation from historical data  
2. Generated random demand values using a normal distribution  
3. Built stockout logic to detect demand exceeding reorder point  
4. Ran a 10,000-iteration Monte Carlo simulation using Excel Data Tables  
5. Evaluated stockout probability for different reorder points  
6. Selected an optimal reorder point based on acceptable stockout risk  

---

## 📊 Key Results
- The Monte Carlo simulation successfully modeled demand uncertainty  
- An optimized reorder point reduced stockout probability to approximately **2–5%**  
- The final inventory policy balances service level and inventory holding risk  

---

## 📈 Conclusion
Monte Carlo simulation is an effective approach for inventory optimization under uncertainty. This project demonstrates how Excel can be used as a powerful analytical tool to support operational decision-making without advanced programming.

---

## 📌 How to Run the Project
1. Open the Excel file in Microsoft Excel  
2. Navigate to the **Simulation** sheet  
3. Adjust the reorder point value  
4. Recalculate the simulation (F9) to observe stockout probability changes  

---

## 👤 Author
Bhavya Jain  
