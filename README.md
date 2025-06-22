#  End-to-End Supply Chain Management Project

An automated and modular supply chain management system designed using low-code/no-code tools integrated with cloud services and databases. This project showcases how to build a seamless pipeline from data ingestion to analysis using **n8n**, **Supabase**, **QuadraticHQ**, **PostgreSQL**, and **Open Exchange Rates**.

---

##  Project Overview

This project demonstrates a complete data flow for supply chain management, starting from email data collection to visualization and analysis. It automates the process of receiving data files via Gmail, storing them in a PostgreSQL database, and visualizing the data through QuadraticHQ for actionable insights.

---

## Tech Stack

- **[n8n](https://n8n.io/)** – Automation tool for workflow orchestration  
- **[Supabase](https://supabase.com/)** – Backend-as-a-Service, used for file and database handling  
- **[QuadraticHQ](https://www.quadratichq.com/)** – Spreadsheet-based data querying and visualization tool  
- **[PostgreSQL](https://www.postgresql.org/)** – Open-source relational database  
- **[Open Exchange Rates](https://openexchangerates.org/)** – Currency conversion API  
- **[Gmail](https://mail.google.com/)** – Email platform for data source integration  

---

## Workflow Architecture

1. **Data Ingestion via Gmail**  
   - Automated workflow in n8n checks Gmail inbox for specific data file attachments (e.g., `.csv`, `.xlsx`).  

2. **File Storage and Processing with Supabase**  
   - Files are extracted by n8n and uploaded directly to Supabase Storage.  
   - Supabase Postgres database stores metadata and structured data.  

3. **Integration with QuadraticHQ**  
   - Supabase is connected to QuadraticHQ to fetch and query the data.  
   - Cleaned and transformed data is displayed in Quadratic's spreadsheet UI for quick insights.

4. **Currency Conversion (Optional)**  
   - Integrated Open Exchange Rates API to fetch real-time currency conversion for international transaction data.

---

---

## 🔧 How to Set Up

### Prerequisites

- n8n installed locally or deployed on cloud (e.g., Docker, Railway, etc.)
- Supabase project set up
- QuadraticHQ account
- Gmail account with access to the files
- API key from OpenExchangeRates.org

### Steps

1. **Set up PostgreSQL schema in Supabase**  
   Import `supabase_schema.sql` to your Supabase project.

2. **Configure n8n workflows**  
   - Connect Gmail, Supabase, and Open Exchange Rates via credentials in n8n.
   - Import and customize workflows based on `.n8n_workflows/`.

3. **Enable Supabase → QuadraticHQ Integration**  
   - In QuadraticHQ, connect the Supabase database using credentials.
   - Pull data and create spreadsheet views or pivot tables.

4. **Visualize and Analyze**  
   - Use Quadratic's UI for data exploration, filtering, and reporting.

---

## Sample Use Cases

- **Order Tracking**: Get live updates of shipments received via email and auto-populate the dashboard.
- **Inventory Management**: Automate stock level updates from supplier emails.
- **International Transactions**: Apply real-time currency conversion to analyze multi-region operations.

---

## Key Highlights

- Fully automated data migration pipeline
- No-code/low-code architecture
- Real-time currency support
- Scalable and modular design
- Cloud-native and secure

---

## Author

**Tirthankar Bagal**  
📧 tirthankarbagal@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/tirthankar-bagal)  
🔗 [GitHub](https://github.com/Tirtho2000)

---
![image](https://github.com/user-attachments/assets/73cac15a-8ce2-47aa-a935-e239c1d372e9)
![image](https://github.com/user-attachments/assets/bdb846b9-de46-43b1-bca1-9c460f11b329)
![image](https://github.com/user-attachments/assets/55545e87-ee87-4ed1-9f20-b6d41ba6ba36)
![image](https://github.com/user-attachments/assets/9d9e4fa3-ef06-47e9-b6b6-4e50b0342c54)
![image](https://github.com/user-attachments/assets/bb075a1c-1c3c-4b77-8478-6e6a77d4efa2)
![image](https://github.com/user-attachments/assets/73dffd28-6bee-46fb-b0ba-906c9b5f3b99)






