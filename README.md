# Student Survey – Power BI Retail Dashboard

This Power BI project analyzes how students in the United States spend money across various product categories such as video games, indoor games, outdoor sports, toys, books, and gadgets. Using the **Student Survey** dataset, the report extracts meaningful insights, applies conditional formatting, and demonstrates dashboard, visualization, and security features.

---

## 📊 Project Overview

**Industry:** Retail  
**Dataset:** Student Survey  
**Tool:** Power BI Desktop (.pbix)

This analysis explores:
- Spending behavior across **Store Location** (Urban, Suburban, Rural)
- Store **Setting** categories (store environment type)
- Age-based purchasing patterns
- Category-wise spending in multiple sports/gaming/product segments

---

## 🛠️ Report Components

### **1. Tabular Visualization – TAP Conditional Formatting**
A table visual shows **Total Amount of Purchase (TAP)** with color rules:
- **Red** → 0 to 34,999  
- **Yellow** → 35,000 to 59,999  
- **Blue** → 60,000 and above  

### **2. Matrix Visualization**
Matrix shows **Outdoor Sports Spending** by:
- Age  
- Store Setting  
with conditional formatting.

### **3. Funnel Chart**
Displays **Total Amount of Purchase by Store Setting**  
with labels shown as **Percentage of First**.

### **4. Pie Chart**
Shows **Total Amount of Purchase by Store Location**, filtered to **Suburban** using filter context.

### **5. Scatter & SandDance Visuals**
- **Scatter Plot:** Video Games Purchase vs. Outdoor Sports Spending by age  
- **SandDance Plot:** Indoor Sports spending vs. Video Games spending across age groups  

### **6. Row-Level Security (RLS)**
Users are restricted based on the **User Mapping Table**.  
Example:
- *Mani → Rural* → Mani only sees Rural data.

### **7. Power BI Service**
- Published to Power BI Cloud Service  
- Dashboard created (Funnel + Scatter)  
- **Scheduled Refresh:** 6 times every 4 hours per day  

### **8. Power BI Q&A Feature**
Two Q&A visuals:
- “Average age of students”  
- Donut chart of Total Amount of Purchase by Store Location
- 
## 📁 Repository Structure

project-root/
├─ pbix/
│ └─ Student_Survey_Report.pbix
├─ README.md
└─ LICENSE 

---

## 📥 How to Use

1. Download the `.pbix` file from the **pbix/** folder.  
2. Open it in **Power BI Desktop**.  
3. Explore visuals, filters, Q&A, and RLS setup.  
4. If RLS is needed:
   - Go to **Modeling → Manage Roles**
   - Load the User Mapping table
   - Test using **View as Role**

## 📄 License

This project is licensed under the MIT License.

MIT License  
Copyright (c) 2025  

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights  
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell  
copies of the Software, and to permit persons to whom the Software is  
furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all  
copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR  
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE  
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER  
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,  
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN  
THE SOFTWARE.


