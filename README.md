
# 📊 Sales Performance Tracker (Excel + Macros)

This project is an Excel-based tracker with formulas, macros, and dashboards for monitoring sales performance against targets.  

## 📘 Project Summary  

The **Sales Performance Tracker** is an Excel-based tool with formulas, macros, and dashboards designed to measure sales against targets.  

- ✅ Automates performance calculations (% to Target)  
- 📊 Provides Sales Performance summaries to show the distribution by performance, performance breakdown, Top performer, Top Region and Lowest performer, Average% to Target and Region Analysis. 
- 📈 Includes an interactive dashboard for quick insights  
- ⚙️ Settings page to send emails to individual sales person or their cumulative performance to managers using trigger buttons.
- 🔄 Macros for refreshing data and visuals  

This tracker helps teams monitor sales activity, identify gaps, and make data-driven decisions efficiently.  
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
- Performance **summaries** page generated on click of a button from the raw data page.
- Interactive **dashboard**
- Email sales alerts for individual sales person or managers/ 
- **Macros** for automated refresh. 




## 🚀 How to Use  

1. **Enter Data in `Raw Data` Sheet**  
   - Input **Salesperson, Region, Month, Sales, and Target values**.  
   - `% to Target` and **Performance** will be calculated automatically.  
   - Run the included **macros** to refresh the dashboard and summary.
   - Also, includes a button if triggered then automatcally sends emails if the % to Target is below 60%

2. **Check the `Summary` Sheet**  
   - Shows Sales Performance summaries to show the distribution by performance, performance breakdown, Top performer, Top Region and Lowest performer, Average% to Target and Region Analysis. 

3. **Explore the `Dashboard` Sheet**  
   - Interactive charts and visuals update automatically after macros are refreshed through the button.

4. **Settings & Instructions**  
   - Use the `Settings` tab to update thresholds or business rules. Purpose: IT sends an Outlook email to the isalesperson or manager with a simple alert message if threshold is crossed.
   - `Macro Instructions` tab explains how to run/update macros.  

---


