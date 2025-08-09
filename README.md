# Student Survey Visualization Dashboard


## Objective

This Power BI project analyzes student spending across various retail stores in the United States based on a survey dataset. It explores insights into purchase behavior on categories like video games, indoor games, toys, books, gadgets, etc., segmented by **Store Location** and **Store Setting**.

**Industry Type:** Retail Store  
**Dataset:** Student Survey 
---

##  Report Visualizations

### **Tabular Visualization**
Total Amount of Purchase (TAP) using conditional formatting:
1. 0 < TAP < 35,000         then Red
2. 35,000 <= TAP < 60,000   then Yellow
3. TAP >= 60,000            then Blue
- Grouped by: `Store Location` and `Store Setting`

### 2. **Matrix Visualization**
- Show the amount spent on **Outdoor Sports**.
- Cross-tabbed by: `Age Groups` × `Store Setting`
- Apply color formatting for total outdoor sports spend.

### 3. **Funnel Chart**
- Show total amount of purchases by `Store Setting`.
- Display **data labels** as **percentage of first**.

### 4. **Pie Chart**
- Display total purchases by `Store Location`.
- Filter to only show for **Suburban** `Store Setting`.

### 5. **Advanced Visuals**
- **Scatter Plot**: 
  - Video games and outdoor sports purchases vs. age.
- **Sand Dance Plot**:
  - Indoor sports and video games spend across age groups.

--- 
