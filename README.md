# Data Science POS System

A lightweight, terminal-based Point of Sale (POS) application designed to simulate retail transaction processing and operational business analytics. Built entirely within Python's data science ecosystem, this system replaces traditional relational databases with optimized, in-memory data structures.

## Core Architecture

The application is structured around three main technical components:

* **Inventory & Log Management (Pandas):** Core tracking operations utilize Pandas DataFrames to maintain structured, indexed product catalogs. It handles real-time stock balances and sequentially appends detailed transactional records to an active historical sales log.
* **Vectorized Calculations (NumPy):** Multi-item checkout mathematics, grand totals, and inventory level deductions are processed using fast, array-based operations rather than standard Python loops.
* **Business Intelligence Dashboard (Matplotlib):** An on-demand analytics engine aggregates transaction logs to generate visual revenue charts and product performance metrics.

## Key Features

* **Interactive CLI:** Simple text-based menu for executing sales, checking stock, and viewing raw database tables.
* **Stock Verification:** Automatic check constraints that prevent sales if requested quantities exceed available shelf stock.
* **Automated Logging:** Timestamps and logs every transaction dynamically for downstream reporting.
* **Visual Dashboards:** Instantly plots total revenue broken down by individual product categories.

## Tech Stack

* **Language:** Python 3
* **Libraries:** Pandas, NumPy, Matplotlib

## Setup & Installation

Since this project runs entirely inside a Jupyter Notebook or a standard Python environment, you can set it up quickly:

1. **Clone or Download the Project:** Download the repository files to your local machine.
2. **Install Dependencies:** Make sure you have the required data science libraries installed via terminal:
   ```bash
   pip install numpy pandas matplotlib
