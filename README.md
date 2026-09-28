# Microsoft-Fabric-Medallion-Architecture-End-to-Project
This repository contains a complete, end-to-end Microsoft Fabric project implementing the Medallion Architecture (Bronze → Silver → Gold) using Data Pipelines,Lakehouse,and a Semantic Model (Direct Lake).
The project is production-aligned, scalable, and suitable for learning, demos, interviews, and real-world Fabric implementations.

## Project Objective
- Ingest multiple CSV files from a single GitHub repository in one pipeline execution
- Store raw data in Bronze (Lakehouse Files)
- Clean and standardize data in Silver (Delta tables)
- Publish analytics-ready datasets in Gold (Delta tables)
- Expose data through a Semantic Model for Power BI reporting

## Source Datasets
All datasets are sourced from Microsoft Learning’s public GitHub repository:
https://raw.githubusercontent.com/MicrosoftLearning/dp-data/main/
<img width="387" height="277" alt="image" src="https://github.com/user-attachments/assets/57b2c6bc-b4c3-48fe-b89a-06b73d4bbf54" />

## Architecture Overview
<img width="287" height="500" alt="image" src="https://github.com/user-attachments/assets/f78d93b8-cb45-4c47-bf54-19535ddf97cd" />

## Lakehouse Structure
<img width="282" height="487" alt="image" src="https://github.com/user-attachments/assets/535ab5a4-cc81-43e3-b76d-7bfd1ffefff9" />

## Data Pipeline Configuration
<img width="352" height="570" alt="image" src="https://github.com/user-attachments/assets/0de976dd-dfcf-4aee-a963-64a8ebc4ec4b" />
<img width="1057" height="275" alt="image" src="https://github.com/user-attachments/assets/a407c98d-c5dd-457b-9e18-5b392c072b4a" />
<img width="671" height="712" alt="image" src="https://github.com/user-attachments/assets/a35d1cf5-4604-49ac-a62a-fcdc094c0fcc" />
<img width="462" height="570" alt="image" src="https://github.com/user-attachments/assets/e147ff1b-2e84-461b-8d99-4e46db6602e3" />
<img width="517" height="536" alt="image" src="https://github.com/user-attachments/assets/f96ee618-8742-4367-8b7e-21e6f4b73082" />
<img width="327" height="421" alt="image" src="https://github.com/user-attachments/assets/6306fb4c-aa83-462e-b5d1-683d9d325295" />
<img width="541" height="850" alt="image" src="https://github.com/user-attachments/assets/9f1e402b-5986-4d48-bc6b-bdac785d8dd2" />









