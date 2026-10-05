# POS Evaluation Data Analysis

This repository contains the data analysis for my MSc Computer Science project. The project involved developing and evaluating a browser-based POS and inventory management system for small textile retailers in Sri Lanka.

Three small retailer shops participated in the project. To protect the identity of the participating retailers, they are referred to as Shop A, Shop B and Shop C.

Manual sales records were collected from 25 July to 24 August 2026. After introducing the POS system, sales data was collected from 3 September to 4 October 2026.

## Dataset Structure

The manual and POS datasets use the same structure. Each row represents one sales transaction.

- `sale_no` - Transaction number
- `order_date` - Date of the transaction
- `order_time` - Time of the transaction
- `different_items` - Number of different product types in the transaction
- `total_items` - Total number of items sold in the transaction
- `order_total` - Total transaction value (LKR)

## Analysis

The main measures analysed are:

- Transactions per recorded sales day
- Items sold per recorded sales day
- Sales value per recorded sales day
- Average items per transaction
- Average transaction value
- Seven-recorded-sales-day moving average of sales

The analysis was performed using Python, pandas and Matplotlib.

## Note

The manual and POS datasets were collected during different calendar periods and under different conditions. Therefore, the differences observed between the two periods are treated as descriptive and cannot be attributed solely to the POS system.
