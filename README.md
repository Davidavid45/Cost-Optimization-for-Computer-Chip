# Introduction

This project analyzes the cost optimization for computer chip production and distribution across five facilities. By comparing proportional and optimized policies, evaluating demand fluctuations, and exploring the adoption of cost-reducing technologies, the study provides actionable recommendations to minimize costs.
Objectives

- Minimize total costs, including production and shipping.
- Evaluate the impact of demand increases on costs and facility capacity.
- Determine the cost-effectiveness of capacity expansions.
- Assess potential savings from technology adoption.

# Methodology

- Data Inputs:
  - Production Costs: Costs per chip across facilities.
  - Shipping Costs: Costs per chip to different regions.
  - Facility Capacities: Maximum production per facility.
  - Regional Demands: Demand distribution across regions.

- Optimization Models:
  - Proportional Policy: Allocates production proportionally to demand.
  - Optimized Policy: Uses Pyomo to determine cost-minimizing allocations.

- Additional Scenarios:
  - 10% Demand Increase: Simulated increased demand to test capacity.
  - 10% Capacity Expansion: Incrementally evaluated for all facilities.
  - Technology Adoption: Simulated a 15% reduction in production costs.

# Results
## Policy Comparison

- Proportional Policy: $56,133,859.96 total cost.
- Optimized Policy: $49,083,430.40 total cost (12.55% cost savings).

## Demand Increase

- Total costs increased to $61,747,245.95 under a 10% rise in demand.
- All facilities stayed within capacity limits.

## Capacity Expansion

- Richmond was the most cost-effective facility for a 10% capacity expansion.

## Technology Adoption

- A 15% production cost reduction resulted in substantial savings, with Richmond and Alexandria yielding the greatest cost-saving potential.

# Technologies Used

- Pyomo: Optimization modeling.
- Pandas: Data manipulation and analysis.
- Matplotlib: Data visualization.
