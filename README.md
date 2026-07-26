# Mobile Money Transaction & Fraud Analytics

## Project overview

This project analyzes synthetic Mobile Money transactions to help a fintech company monitor its activity, understand transaction patterns, and identify fraudulent operations.

The project follows an end-to-end Data Analyst workflow using Python, PostgreSQL, Excel, and Power BI.

> Project status: In progress

## Business context

A Mobile Money company needs a reliable monitoring system to evaluate transaction performance and strengthen fraud surveillance.

The analysis aims to answer the following questions:

- How many transactions are processed?
- What is the total transaction value?
- Which transaction types generate the highest volume and value?
- At what times is transaction activity the highest?
- What proportion of transactions is fraudulent?
- Which transaction types are most exposed to fraud?
- How effective is the existing fraud detection system?
- What operational indicators should management monitor?

## Project objectives

- Clean and validate transaction data
- Explore transaction behavior and activity trends
- Calculate business and fraud monitoring indicators
- Query transactional data using PostgreSQL
- Build an Excel analysis report
- Create an interactive Power BI dashboard
- Produce actionable recommendations for decision-makers

## Tools

- Python: data cleaning, exploration and feature engineering
- PostgreSQL: data storage and business queries
- Excel: Power Query, PivotTables and advanced formulas
- Power BI: data modeling and interactive dashboards
- Git and GitHub: version control and project documentation

## Dataset

The project uses the PaySim synthetic financial dataset.

PaySim simulates Mobile Money transactions based on aggregated information from a real Mobile Money service. Synthetic data is used because real financial transactions are generally confidential.

Main variables include:

- Transaction time
- Transaction type
- Transaction amount
- Sender and recipient identifiers
- Sender and recipient balances
- Fraud status
- Fraud alert status

Dataset source: [PaySim on Kaggle](https://www.kaggle.com/datasets/ealaxi/paysim1)

## Repository structure

```text
Projet_fintech/
├── data/
│   ├── raw/
│   ├── processed/
│   └── sample/
├── notebooks/
├── sql/
├── src/
├── excel/
├── powerbi/
├── images/
├── reports/
├── .gitignore
├── LICENSE
└── README.md