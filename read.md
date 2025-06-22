# Supply Chain Concepts & Metrics

This document provides a concise understanding of key business metrics and concepts commonly used in supply chain management. These insights are particularly useful for professionals in planning, warehousing, distribution, and customer satisfaction roles.

---

## Core Concepts

### Orders and Lines

- **Order**: A unique request placed by a customer on a specific date.
- **Order Line**: Each item within an order is referred to as an "order line".

**Example**:  
A customer orders 4 notebooks and 2 pens on Amazon. This entire purchase has one order ID with two order lines:
- Order Line 1: Notebooks (Qty: 4)  
- Order Line 2: Pens (Qty: 2)

---

## Key Performance Metrics

### 1. Line Fill Rate

- **Definition**: Measures how many lines were shipped out of the total order lines.
- **Focus**: It only counts whether a line was fulfilled, not how much of it was fulfilled.
- **Use**: Crucial for the **Supply Planning Team**.

**Formula**:  
`Line Fill Rate = Fulfilled Order Lines / Total Order Lines`

**Example**:  
If Amazon ships 4 notebooks but only 1 of the 2 pens:  
- Fulfilled lines = 1 (Notebook)
- Total lines = 2 (Notebook + Pen)  
  **Line Fill Rate = 1/2 = 50%**

---

### 2. Volume Fill Rate (Case Fill Rate)

- **Definition**: Measures total quantity shipped versus total quantity ordered.
- **Use**: Useful for evaluating the supply planning effectiveness.

**Formula**:  
`Volume Fill Rate = Total Quantity Shipped / Total Quantity Ordered`

**Example**:  
- Ordered: 4 notebooks + 2 pens = 6 items  
- Shipped: 4 notebooks + 1 pen = 5 items  
  **Volume Fill Rate = 5/6 = 83%**

---

### 3. On Time Delivery %

- **Definition**: Assesses if the **entire order** (not just lines) was delivered as per the agreed delivery time.
- **Use**: Critical for the **Warehouse & Distribution Teams**.

**Condition**:  
Order is **On Time** only if **all line items** are delivered within the agreed timeframe.

---

### 4. In Full Delivery %

- **Definition**: Checks if the order was fulfilled completely with the exact requested quantity.
- **Use**: Vital for the **Supply Planning Team**.

**Condition**:  
Order is **In Full** only if **all line items** are delivered in full quantity.

---

### 5. On Time In Full (OTIF) %

- **Definition**: Evaluates whether an order was delivered both **on time** and **in full**.
- **Use**: Important for **all supply chain sub-functions** — planning, warehousing, logistics.

 **Condition**:  
An order qualifies as **OTIF** only when **every item** in the order is delivered **completely and on time**.

 **Significance**:  
OTIF is a tough but critical KPI reflecting the **reliability** and **customer satisfaction** of your supply chain operations.

---

## Summary Table

| Metric              | Level    | Measures                      | Important For               |
|---------------------|----------|-------------------------------|-----------------------------|
| Line Fill Rate      | Line     | Lines fulfilled               | Supply Planning Team        |
| Volume Fill Rate    | Quantity | Total quantity fulfilled      | Supply Planning Team        |
| On Time Delivery %  | Order    | Timeliness of full delivery   | Warehouse & Distribution    |
| In Full Delivery %  | Order    | Fulfillment of full quantity  | Supply Planning Team        |
| OTIF %              | Order    | Full + Timely delivery        | All Supply Chain Functions  |

---

## Author

**Tirthankar Bagal**  
tirthankarbagal@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/tirthankar-bagal)  
🔗 [GitHub](https://github.com/Tirtho2000)

---

