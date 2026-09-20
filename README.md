# Project_OlaCars

### Project Overview

Built a cloud-based data engineering solution for Ola Cars to ingest, process, transform, and analyze vehicle, customer, booking, driver, and transaction data using Microsoft Azure.

The solution follows a Medallion Architecture (Bronze → Silver → Gold) to build scalable and reliable data pipelines and prepare curated datasets for analytics and reporting.

### data extract from SQL Database (use GITHUB as application data source)

<img width="1716" height="744" alt="image" src="https://github.com/user-attachments/assets/a3b558ac-f9a5-44f5-ab10-af9f56c0d58e" />

### source github with http dataset format "csv"

linked service = http/base URL/relative URL

<img width="1831" height="814" alt="image" src="https://github.com/user-attachments/assets/76f720f5-2e8c-4123-92cc-4e2527b79933" />

### sink data to SQL database (using table name which is already created with schema)

<img width="1387" height="617" alt="image" src="https://github.com/user-attachments/assets/472cf4b7-0a9b-47c2-a9a4-958bc6e76b3a" />

### TEST COPY ACTIVITY
<img width="1539" height="562" alt="image" src="https://github.com/user-attachments/assets/2990d1e9-b356-47da-b8a1-c042fc11aff0" />


incremental pipeline to data lake runs successful


<img width="1822" height="755" alt="image" src="https://github.com/user-attachments/assets/52d7b1f3-d599-4416-838e-8616702a1edf" />





