# Route Assignment Optimization
This project focuses on optimizing route assignments for a supply chain dataset. We aim to minimize transportation and warehousing costs while adhering to various constraints and business rules. This README provides an overview of the project, its components, and how to run the code.

## Introduction
Supply chain optimization involves assigning routes to orders while considering factors like weight restrictions, plant capacities, historical data, and costs. We use Python for data analysis and PuLP for linear programming to achieve route optimization.

## Data
We are working with seven tables:
  
OrderList: Order information, including Order ID, Date, Origin, Destination, Product, Weight, etc.  
FreightRates: Freight rates for different carriers and routes.  
WhCosts: Warehouse costs per unit for various plants.  
WhCapacities: Daily capacity for each warehouse (plant).  
ProductsPerPlant: Mapping of products to plants.  
VmiCustomers: Mapping of customers to plants.  
PlantPorts: Mapping of plants to ports.  

## Setup
### Prerequisites  
Python 3.x  
Pandas  
NumPy  
PuLP  

## Route Assignment Optimization
We use linear programming to optimize route assignments. The main steps include:
  
Data Preprocessing: Clean and format the data.  
Define Decision Variables: Create binary decision variables to assign orders to routes.  
Define Objective Function: Minimize transportation and warehousing costs.  
Add Constraints: Add constraints based on business rules and data.  
Solve the Optimization Problem: Use PuLP to solve the linear program.  
Interpret the Results: Analyze the optimized route assignments and costs.

## Results
The results include optimized route assignments and associated costs. These results can help in decision-making to minimize costs in the supply chain.

## Usage
Provide instructions on how to run the code and perform the route assignment optimization.

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.