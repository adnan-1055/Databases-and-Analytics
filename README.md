# Databases and Analytics Assignment — NorthStar Urban Mobility and Logistics

## Overview
This repository contains the analytical notebooks for the Databases and Analytics 
module assignment (CP60056E) at the University of West London. The case study is 
based on NorthStar Urban Mobility and Logistics, a regional UK transport company 
facing operational inefficiencies, rising complaints, and fragmented data systems.

## Repository Structure
| Notebook | Description |
| `NorthStar_SQL_R.ipynb` | SQL queries using sqldf in R + R analytics with ggplot2 |
| `NorthStar_Python.ipynb` | Data processing and visualisation using Pandas, NumPy, Matplotlib and Seaborn |
| `NorthStar_MongoDB.ipynb` | MongoDB Atlas NoSQL database design, PyMongo CRUD operations, indexing and query optimisation |

## Technologies Used
- R (sqldf, ggplot2)
- Python (Pandas, NumPy, Matplotlib, Seaborn, PyMongo)
- MongoDB Atlas
- Google Colab

## Dataset
The NorthStar dataset contains 10 CSV files covering orders, deliveries, customers, 
drivers, vehicles, complaints, incidents, hubs, app events and a data dictionary.

## Key Findings
- 35% of deliveries are delayed or failed
- RiversSide zone has the highest delivery failure rate
- High severity complaints take an average of 13 days to resolve
- Indexing reduced MongoDB query scan from 950 to 132 documents (86% improvement)

## Module
University of West London — Databases and Analytics (CP60056E)
