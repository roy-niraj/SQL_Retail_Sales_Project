# sql_retail_sales_project_01

Project Overview

Project title: Retail Sales Analysis
Database: sql_project

This project is designed to demonstrate SQL skills and techniques tipically used by data analysts to explore to, clean , and analyze retail sales data. The project setting up a retail sales database , performing exploratory data analysis (EDA), and answering specific business questions through SQL queries. This project is ideal for those who are their journey in data analysis and want to build a solid foundation in SQL.

Objectives:
1. Set up a retail sales database : Create and populate a retail sale databse with the provided sales data.
2. Data cleanig :  Identify and removes any records with the missing values or null value.
3. Exploratory Data Analysis(EDA) : Perform basic exploratory data analysis to understanding the dataset.
4. Business Analysis : Use SQL to answer specific business question and derive insights from the sales data.

Project Structures
* Database Creation : The project starts by creating named sql_project.
* Table Creation : A table named retail_sales is created to store the sales data. The table structure includes columns for trasaction ID, sale data, sale time, suctomer ID, gender, age, product catogory , quantity sold , price per unit, cost of good sold and total sale amount.


DROP DATABASE IF EXISTS sql_project_01 
CREATE DATABASE sql_project_01;


DROP TABLE IF EXISTS retail_sales;
CREATE TABLE retail_sales
	(
		transactions_id INT PRIMARY KEY,
		sale_date DATE,
		sale_time TIME,
		customer_id INT,
		gender VARCHAR(15),
		age INT,
		category VARCHAR(20),
		quantity INT,
		price_per_unit FLOAT,
		cogs FLOAT,
		total_sale FLOAT

	);

