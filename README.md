# ETL

__Context__: We are simulating a scenario where our company, Netfluxter (Netfluxter allows customer to rent Netflix movies), has data stored in different locations like a MySQL server, MongoDB, and locally as CSV files. The goal is to gather information from these different sources and build a dimensional data mart that mirrors a specific business process, such as retail sales, inventory management, etc.

Specifically, for Netfluxter, we'll be using data from the Sakila MySQL database for customer-related datails like payments and rentals. Payment data will be uploaded onto MongoDB before we start the ETL process, mimicking a real scenario. For movie data, we'll use the "Netflix Movies and TV Shows" dataset available on Kaggle. My task is to design and create a dimensional data mart focused on rental transactions. The fact table (fact_rentals) will allow Netfluxter to analyze various aspect of their rental operations, such as rental trends over time, popular movies, store performance, etc.

__Task__: First, design the dimensional data mart. Then, develop an ETL pipeline to extract, transform, and load data into the data mart. Finally, write SQL queries to demonstrate that everything is functioning correctly.
