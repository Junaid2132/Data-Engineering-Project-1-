 NYC Taxi Data Engineering Pipeline

📌 Project Overview

This project demonstrates a complete Data Engineering workflow using NYC Taxi trip data. It includes automated data ingestion, SQL-based analysis, data quality monitoring, and full containerization for reliable deployment.

🛠️ Tech Stack

Python (Pandas):

Used for robust data manipulation and cleaning.

SQLite / PostgreSQL: 

SQL databases used for efficient data storage and querying.

Docker & Docker Compose:

Used to containerize the environment for consistent execution.

Matplotlib: 

Utilized for generating visual analytics and Data Quality reports.

🚀 Key Features

Automated Ingestion:

Scripts to automatically read CSV datasets and load them into a structured SQL table.

Data Quality Assurance:

An automated reporting system that monitors missing values and visualizes the "Success Rate" of clean data.

Visual Analytics: 

Distribution analysis of trip durations and bar charts for data ingestion status.

Containerized Deployment: 

Optimized Docker configuration (Dockerfile and docker-compose.yaml) for one-click environment setup.

Setup and Execution :

✓ Clone the repository
git clone https://github.com/Junaid2132/NYC-Taxi-Data-Project
✓ Run with Docker
"The Docker configuration and ingestion scripts are integrated within the Jupyter Notebook for easy execution."
docker-compose up --build

