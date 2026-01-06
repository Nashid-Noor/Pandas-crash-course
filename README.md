# Pandas Crash Course

A hands-on introduction to the Pandas library for data manipulation and analysis in Python. This project contains a Jupyter Notebook (`main.ipynb`) that demonstrates essential Pandas operations.

## Overview

The notebook covers the following key concepts:

-   **DataFrames**: Creating DataFrames from dictionaries.
-   **Indexing**: Accessing data by columns and rows (`iloc`).
-   **Filtering**: Selecting data based on conditions.
-   **Updating**: Modifying values in the DataFrame.
-   **Deleting**: Removing rows from the DataFrame.
-   **Data Cleaning**: Handling missing values (`dropna`, `fillna`).
-   **Data Analysis**: performing basic analysis like `value_counts`, `mean`, and `groupby` operations.
-   **Saving**: Exporting modified data to CSV files.

## Prerequisites

-   Python 3.13 or higher
-   [uv](https://github.com/astral-sh/uv) (recommended for dependency management)

## Installation

This project uses `uv` for dependency management.

1.  Clone the repository:
    ```sh
    git clone <repository_url>
    cd Pandas-CrashCourse
    ```

2.  Sync dependencies:
    ```sh
    uv sync
    ```

## Usage

You can explore the notebook using Jupyter.

1.  Run the notebook:
    ```sh
    uv run jupyter notebook main.ipynb
    ```

2.  Execute the cells to follow along with the examples.

## Files

-   `main.ipynb`: The main notebook containing code examples.
-   `pyproject.toml`: Project configuration and dependencies.