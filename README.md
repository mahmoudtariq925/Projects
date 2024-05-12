# Data Feed Calculator

This repository hosts the Python code and Jupyter notebooks for the Feed Mix Optimization project. The project employs linear programming to develop an optimized agricultural feed mix. We aimed to minimize both the number of ingredients and the costs while ensuring that the nutritional standards are met. The project outcomes include a streamlined ingredient list, cost reductions, and a strategic decision-support tool for optimizing feed compositions.


The project was structured around several key objectives:

 - Model Development: Construct a linear programming model that incorporates combined ingredient rules. These rules define the maximum allowable proportions for specific combinations of ingredients to ensure a balanced feed composition.
 - Ingredient Optimization: Use binary variables to decide the inclusion of each ingredient, thereby minimizing the number of different ingredients used. This simplifies procurement and supply chain logistics.
 - Cost Reduction: Adapt the model to minimize the cost of the feed mix by selecting the most cost-effective combination of the necessary ingredients.
 - Trade-Off Analysis: Analyze and visualize the trade-offs between reducing the number of ingredients and minimizing costs, facilitating informed decision-making.


#### Data Preparation:
 The notebook starts by loading and preparing data, setting up necessary parameters for the optimization model.
#### Model Setup:
 Defines the linear programming model, including variables, objective functions, and constraints based on the nutritional and cost requirements.
#### Optimization Execution: 
 Runs the optimization to determine the optimal combination of ingredients.
 
 ## Outputs

The notebook outputs:

 - **Optimized Feed Mix**: Details the minimal number of ingredients used and the corresponding cost-efficient feed mix.
 - **Visualizations**: Displays graphs depicting the relationship between the number of ingredients and the cost, aiding in strategic decisions.

