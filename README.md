# # Somato Business Insights Project

## Overview:
This GitHub repository contains a comprehensive analysis of key metrics for Somato, a food delivery platform. The insights aim to provide a thorough understanding of quarterly performance, order accuracy, top customers, monthly sales trends, payment mode correlations, and restaurant performance.

## Insights:

### 1. Quarterly Performance
   - **Description:** Quarterly overview of Somato's business performance.
   - **Relevant Formulas:** N/A

### 2. Order Accuracy
   - **Description:** Calculation of order accuracy percentage based on delivered and fixed quantity.
   - **Relevant Formulas:**
     - Order Accuracy % = DIVIDE([Delivered], [FIXED QNT], 0)
     - Delivered = CALCULATE(SUM('Somato Order Data'[quantity]), 'Somato Order Data'[deliver_status]="Delivered")
     - FIXED QNT = CALCULATE([sum of qnt], ALL('Somato Order Data'))
     - Cancelled = CALCULATE(SUM('Somato Order Data'[quantity]), 'Somato Order Data'[deliver_status]="Cancelled")

### 3. Top 10 Customers by Customer ID
   - **Description:** Identification and ranking of the top 10 customers based on their customer IDs.
   - **Relevant Formulas:** N/A

### 4. Sales Quantity by Months (Graphical Representation)
   - **Description:** Visualization of sales quantity trends over different months.
   - **Relevant Formulas:** N/A

### 5. Relationship of Payment Modes with Quantity
   - **Description:** Analysis of the correlation between payment modes and order quantity.
   - **Relevant Formulas:** N/A

### 6. Restaurant Performance
   - **Description:** Evaluation of the performance of restaurants associated with Somato.
   - **Relevant Formulas:** N/A

## How to Use:
1. Clone the repository to your local machine.
2. Open the provided data set in a compatible tool.
3. Execute the relevant formulas for insights calculation.
4. Visualize insights through graphs or tables as needed.

Feel free to reach out for any clarifications or additional information.

Happy Analyzing!
[Your Name/Username]
