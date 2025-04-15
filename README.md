## 📄 Abstract

This study presents an optimization framework for electric vehicle (EV) charging station placement in Montreal using Genetic Algorithms (GA) and their advanced variants (Modified GA and Adaptive GA). By minimizing total deployment costs while ensuring sufficient service coverage based on real-world traffic demand data, the project offers insights into cost-effective and scalable infrastructure planning for urban EV networks.

## 🔍 Problem Statement

To meet the growing demand for EV charging infrastructure, we formulate a **cost-minimization problem** that considers:
- Deployment costs
- Traffic node demands
- Station capacity limits
- Penalties for exceeding capacity
- Coverage radius constraints

## 🧠 Optimization Approach

The optimization problem is solved using **Genetic Algorithms** with three variants:
- **Standard GA**: Baseline performance with basic selection, crossover, and mutation.
- **Modified GA (MGA)**: Introduces elitism and reduces mutation rate for faster convergence.
- **Adaptive GA (AGA)**: Dynamically adjusts mutation/crossover rates based on population diversity to balance exploration and exploitation.

## 🧪 Experimental Setup

- **Population Size**: 20  
- **Generations**: 50  
- **Mutation Rates**: GA (0.1), MGA (0.05), AGA (adaptive)  
- **Crossover Rate**: 0.9  
- **Selection**: Tournament Selection  
- **Metrics Evaluated**: Cost minimization, coverage percentage, convergence speed, diversity

## 📊 Results Summary

| Metric                     | Standard GA | Modified GA | Adaptive GA |
|---------------------------|-------------|-------------|-------------|
| Cost Minimization         | Moderate    | Good        | **Best**    |
| Coverage (%)              | 85          | 90          | **95**      |
| Convergence Speed         | 50 gen      | **40 gen**  | 45 gen      |
| Solution Diversity        | Moderate    | Low         | **High**    |
| Scalability               | Good        | Good        | **Excellent**|

## ✅ Conclusion

The **Adaptive GA** was found to be the most effective method, balancing performance across all evaluation metrics. The study suggests that bio-inspired algorithms are well-suited for large-scale, real-world EV infrastructure planning, with room for future improvements via hybrid models and real-time data integration.

## 🏗️ Future Work

- Hybrid GA + PSO / Simulated Annealing methods
- Real-time demand adaptation
- Multi-objective optimization (e.g., environmental impact, grid load)
- Integration of user feedback and behavioral data
- Parallel computing for faster runtime
