# 5 Synthetic Data Analysis Projects

Welcome to my data analysis portfolio. My name is Vladyslav Hubanov, and this repository serves as a curated collection of my work, demonstrating my skills in transforming raw data. I used synthetic projects in this case

My approach is to build a clear, logical path from the initial synthetic data to the final conclusion, ensuring every insight is built on a solid foundation of clean data and sound methodology. Each project below is a self-contained Jupyter Notebook that outlines a business problem, my analytical process, and the data-driven solution.

## Portfolio Projects

Here you will find a selection of projects showcasing my skills across various domains, from financial analysis to geospatial logistics and statistical testing.

### 1. Financial Time-Series Analysis  [<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>](https://colab.research.google.com/github/vlad-gby/ds_5_mini-projects/blob/main/01_fin_time-s_analysis/notebook.ipynb)


* **Scenario:** Performed a quantitative analysis on daily stock price data to identify key financial metrics.
* **Skills Demonstrated:** Time-series indexing, calculating daily returns with `.shift()`, computing rolling volatility with `.rolling().std()`, and using standard deviation to flag anomalous high-volume trading days.



### 2. Geospatial Analysis: Logistics Optimization

* **Scenario:** Solved a logistics problem by determining the closest distribution warehouse for each retail store based on latitude and longitude.
* **Skills Demonstrated:** Implementing the Haversine formula in a vectorized NumPy function, performing a `cross` merge to create all possible store-warehouse pairings, and using `.groupby().idxmin()` for efficient optimization.
* [**View the Notebook**](geospatial_analysis.ipynb)

### 3. A/B Test Significance Analysis

* **Scenario:** Determined if a change in a website's button color resulted in a statistically significant increase in user conversion.
* **Skills Demonstrated:** Implementing a permutation test from scratch in NumPy, calculating a p-value to measure statistical significance, and clearly interpreting the results to drive a business decision.
* [**View the Notebook**](ab_test_analysis.ipynb)

### 4. Monte Carlo Simulation for Business Viability

* **Scenario:** Built a Monte Carlo simulation to forecast the potential annual profit of a new pizza shop in Bergamo, modeling uncertainty in daily customers and costs.
* **Skills Demonstrated:** Random data generation with NumPy, vectorized arithmetic for financial modeling, calculating key performance indicators (total profit, profitable days, best/worst days), and using `np.select` for performance categorization.
* [**View the Notebook**](monte_carlo_simulation.ipynb)

### 5. Machine Learning Pre-processing Pipeline

* **Scenario:** Simulated a critical pre-processing pipeline for a computer vision model, preparing image metadata for analysis.
* **Skills Demonstrated:** Handling complex, nested data structures (a Pandas Series of NumPy arrays), parsing string data to create image arrays of varying dimensions, and using `.apply()` with lambda functions to perform row-wise normalization.
* [**View the Notebook**](image_processing_simulation.ipynb)

Thank you for taking the time to review my work. I am always looking for new and exciting problems to solve.
