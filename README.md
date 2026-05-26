PGO ENG 12 – Advanced Java Stream API Exercises

This repository contains a complete implementation of the Stream API laboratory assignment prepared for the PGO ENG 12 course.

The project was developed in Java 17 and demonstrates practical usage of modern functional-style programming techniques with the Java Stream API. The implementation focuses on writing clean, readable, and efficient stream pipelines without mutating external collections.

Assignment Objectives

The main goal of this project is to practice:

filtering and transforming data
flattening nested collections with flatMap
sorting and aggregation
grouping and partitioning data
working with Optional and OptionalDouble
collecting stream results into lists and maps
generating statistical summaries using DoubleSummaryStatistics
Project Overview

The application simulates a small order management system containing:

customers
products
order items
order statuses
order statistics and reports

All tasks are implemented inside the StreamApiTasks.java class using Stream API operations and collectors.

Implemented Features
Core Tasks
Extract active order IDs
Find orders above a selected value
Generate a sorted list of unique customers
Extract product names from active orders
Calculate total revenue
Compute average delivered order value
Count orders by status
Calculate revenue by product category
Find top customers by spending
Partition expensive and regular orders
Find the most expensive delivered order
Extra Task
Generate complete statistical summaries for active orders using DoubleSummaryStatistics
Technical Details
Language: Java 17
IDE: IntelliJ IDEA
Programming Style: Functional / Stream-based
Libraries: Standard Java Library only
Additional Notes
Stream pipelines are written across multiple lines for readability.
The project avoids reusing consumed streams.
Optional values are handled safely without unsafe access.
No external libraries were used.
Author

Sıla Koçak
