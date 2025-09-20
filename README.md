
# 📊 Sales Performance Tracker (Excel + Macros)

This project is an Excel-based tracker with formulas, macros, and dashboards for monitoring sales performance against targets.  

---

## 🚀 How to Use  

1. **Enter Data in `Raw Data` Sheet**  
   - Input **Salesperson, Region, Month, Sales, and Target values**.  
   - `% to Target` and **Performance** will be calculated automatically.  
   - Run the included **macros** to refresh the dashboard and summary.  

2. **Check the `Summary` Sheet**  
   - Shows aggregated results like **Sales Count by Region**.  

3. **Explore the `Dashboard` Sheet**  
   - Interactive charts and visuals update automatically after macros are refreshed.  

4. **Settings & Instructions**  
   - Use the `Settings` tab to update thresholds or business rules.  
   - `Macro Instructions` tab explains how to run/update macros.  

---

## 📑 Data Format Requirements  

When entering data in the **Raw Data** sheet, follow this structure:  

| Column        | Format / Requirement |
|---------------|----------------------|
| **Salesperson** | Text (e.g., `John Doe`) |
| **Region**      | Text (must match defined regions, e.g., `North`, `South`) |
| **Month**       | Date or Month Name (e.g., `Jan-2025` or `01/01/2025`) |
| **Sales ($)**   | Numeric (whole number or currency, e.g., `5000`) |
| **Target ($)**  | Numeric (whole number or currency, e.g., `6000`) |
| **% to Target** | Auto-calculated (do not edit) |
| **Performance** | Auto-assigned based on % to Target |

⚠️ **Important Notes**  
- Do not overwrite formula columns (`% to Target`, `Performance`).  
- Avoid blank rows inside your data, as they may break formulas/macros.  

---

## 🛠 Features  

- Automated **performance calculation** (% to target).  
- Region-wise **summaries**.  
- Interactive **dashboard** with charts.  
- Configurable **thresholds** via Settings.  
- **Macros** for automated refresh. 
