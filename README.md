# Tea Sales Performance Analysis
> *Project conducted: May 2025 (was not uploaded at the time)*

Uncovering actionable business insights from tea product sales data through exploratory data analysis and visualization.

---

## Introduction

This project focuses on analyzing sales data from a Vietnamese tea business. The dataset includes detailed transaction records covering order times, customer segments, product categories, quantities sold, and revenue generated.

**Project Objective:**  
To derive key insights about customer behavior, product performance, and revenue trends to support strategic decision-making for marketing, inventory, and sales optimization.

---

## Dataset

### Source
The dataset was provided internally by the tea business for analysis. It contains **pre-cleaned transactional data**, ready for direct exploratory data analysis.

### Key Columns
- `Thời gian tạo đơn`: Order creation timestamp  
- `Mã đơn hàng`: Order ID  
- `Mã khách hàng`: Customer ID  
- `Tên khách hàng`: Customer name  
- `Mã PKKH`: Customer segment code  
- `Mô tả Phân Khúc Khách hàng`: Customer segment description  
- `Mã nhóm hàng`: Product category code  
- `Tên nhóm hàng`: Product category name  
- `Mã mặt hàng`: Product ID  
- `Tên mặt hàng`: Product name  
- `SL`: Quantity sold  
- `Đơn giá`: Unit price  
- `Thành tiền`: Total revenue per line item

---

## Tools & Technologies

- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn
- **Tools**: Tableau
- **Notebook**: Jupyter Notebook (.ipynb)

---

## Project Workflow

1. **Data Understanding**:
   - Loaded dataset and reviewed column meanings, data types, and business context.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed total sales by product category and individual product.
   - Identified top-selling products and highest revenue contributors.
   - Evaluated sales distribution across customer segments.
   - Explored order frequency and customer purchase patterns.

3. **Insight Generation**:
   - Generated actionable business insights (e.g., key customer groups, best-selling items, seasonal trends).
   - Suggested strategic recommendations to increase sales and optimize product offerings.
   - Compiled actionable recommendations in the `code_insights_decisions.ipynb`

4. **Visualization**:
   - Created bar plots, pie charts, and trend lines to visualize key metrics and support storytelling.
   - You can refer to this link [Tableau Public Dashboard](https://public.tableau.com/app/profile/nguy.n.kh.nh6448/viz/data_story_telling_W9_new/Story?fbclid=IwY2xjawLMvstleHRuA2FlbQIxMABicmlkETE4emRCVFlnY2lyazQybXFtAR5F7s2D8xUMPrTup_0dNM7dU0iiojzK0cNbAkGEOOm9mkVJnnauZN5KBMedSA_aem_KFFoiVQxIUl2ptgfGlWacA) or `tea_sales_dashboard.twbx`.

---

## Key Insights (Preview)

- Certain customer segments (e.g. office workers aged 36–45) contribute significantly to high-value orders.  
- Bột cần tây (celery powder) is a consistently top-selling product, indicating strong demand in detox and health-focused customer groups.  
- Combo sets (e.g. trà hoa cúc trắng set) are popular purchases, suggesting potential for bundling promotions.  
- Sales volume is dominated by core SKUs, implying inventory planning should prioritize these items for stock availability.
- For full insight breakdowns and strategic recommendations, please refer to the `code_insights_decisions.ipynb` included in this repository.
---

## Learning Outcomes

- Practiced exploratory data analysis techniques on real business datasets.  
- Developed data storytelling skills to communicate insights effectively.  
- Strengthened ability to translate raw sales data into strategic business decisions.

---

## Files

- **Dataset**: `data_tea_sales.csv`  
- **Analysis Notebook**: `code_insights_decisions.ipynb`

*For full insights, visualizations, and recommendations, please refer to the Jupyter Notebook included in this repository.*

