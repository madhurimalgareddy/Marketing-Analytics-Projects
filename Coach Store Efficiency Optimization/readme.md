# Coach Store Efficiency Optimization
## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Objective](#objective)
- [Insights](#insights)
- [Conclusion](#conclusion)
  
## Introduction
Coach, a renowned American luxury leather goods brand, specializes in handbags, luggage, wallets, and accessories. Established in 1941, the company pioneered high-quality, durable leather handbags, shaping the premium market. With a strong retail presence across North America, Coach operates both full-price and factory outlet stores to cater to diverse customer segments. This report analyzes key sales drivers across Coach’s retail stores, leveraging data on store size, sales associates, and merchandise value to optimize performance.
## Technologies
Excel VBA macros
Solver
## Objective
The objective of this case study is to analyze the key factors influencing sales performance across Coach’s retail stores. By examining store size, number of sales associates, and merchandise value, the study aims to identify patterns and drivers of sales variability. The findings will help optimize store operations, enhance sales efficiency, and inform strategic decisions to maximize revenue and profitability.
## Insights
![Screenshot 2025-03-15 163839](https://github.com/user-attachments/assets/9376a500-caa8-45a2-abeb-40e718f50a4d)

### Efficient vs. Inefficient Stores:

Seven stores (Store 1, Store 6, Store 2, Store 3, Store 9, Store 10, Store 14) have an efficiency score of 1.00, indicating that they are operating efficiently based on inputs (square footage, associates payroll, display merchandise) relative to their sales performance.
The remaining seven stores have efficiency scores below 1.00, indicating room for improvement in how resources are utilized to drive sales.   

### Differences in Input Utilization:

Stores with high efficiency tend to have a balanced mix of input utilization (associates payroll, display merchandise) compared to their sales output.
Inefficient stores may either be underperforming in sales relative to their inputs or not optimizing their available resources effectively.   

### Handbag Sales as a Key Driver:

Stores with higher handbag sales tend to have better efficiency scores. This suggests that handbags are the dominant revenue driver for Coach stores. Stores struggling with handbag sales may need to re-evaluate product placement, pricing strategies, or customer engagement.   

### Potential Optimization Strategies:

Stores with lower efficiency scores might need better allocation of payroll hours, improved display merchandising, or adjusted sales strategies to improve performance.
Identifying the best practices from efficient stores and implementing them in less efficient stores could enhance overall profitability.
## Optimization Strategy We Followed:

![image](https://github.com/user-attachments/assets/33009f0e-517f-4558-b4c1-c4c82c45f4e1)

![image](https://github.com/user-attachments/assets/a384ed34-a996-4435-bf6f-d4ec7b1785f4)

### Efficiency Evaluation:

The first image shows a breakdown of inefficient stores and how their performance is benchmarked against efficient stores using best practice weights.
The second image provides detailed input-output comparisons and Solver-derived optimal weights.   

### Weight Allocation:

Inefficient stores are mapped to efficient stores with specific weights, showing how they can optimize performance by mimicking the best practices of efficient stores.
For instance, Store 3 has a weight of 0.30 from Store 4 and 0.26 from Store 11, meaning these stores serve as benchmarks for Store 3.

### Performance Gap:

The Solver output shows how inefficient stores need to adjust their input usage (square footage, payroll, display merchandise) to achieve optimized output levels.
For example, Store 7 has inputs (2,720 sq ft, 1,875 payroll/wk, 6,800 display merchandise) and outputs (10,600 gift sales, 465,700 ready-to-wear sales, 60,720 men's styles sales, 1,800,250 handbag sales). When optimized, the combined input-output values from efficient stores indicate potential improvements.

### Optimization Results:

The combined efficient store input-output values (weighted) serve as a benchmark for the inefficient stores.
If an inefficient store aligns with these optimized values, it can improve its efficiency.

## Conclusion:
The analysis helps in identifying underperforming stores and provides a data-driven approach to improving their efficiency.
By redistributing inputs based on best practices, inefficient stores can achieve higher sales without necessarily increasing costs.
The results can be used to strategize operational adjustments such as workforce allocation, merchandising strategies, and sales target optimization.
