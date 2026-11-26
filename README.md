# Energy Consumption Optimization

## 1. Project Overview

This project focuses on analyzing and optimizing electricity consumption for a household or a small building.

The main goal is to minimize total electricity costs while satisfying specific energy consumption constraints.

The project explores convex optimization, introduces non-convex modifications to the model, and then applies suitable techniques to restore convexity.

## 2. Project Objectives

- Analyze household or small-building electricity consumption.
- Minimize total electricity costs.
- Apply optimization techniques using CVXPY.
- Study the convexity of the mathematical model.
- Introduce non-convex components and analyze their effects.
- Restore convexity and compare different model versions.
- Visualize the relationship between electricity consumption and cost.

## 3. Project Parts

The project is divided into five main parts:

**Part 1: Energy Model Setup**

Build an optimization model using electricity consumption data. Define the objective function and constraints, then solve the model using CVXPY.

**Part 2: Convexity Analysis**

Analyze the objective function and constraints to determine whether the original optimization model is convex, with mathematical justification.

**Part 3: Non-Convex Model**

Modify the original model by introducing non-linear terms or other suitable modifications to create non-convex behavior.

**Part 4: Restoring Convexity**

Modify the non-convex model to restore convexity using suitable mathematical techniques.

**Part 5: Visualization**

Visualize and compare the original convex model, the modified non-convex model, and the restored convex model using graphs.

## 4. Tools and Technologies

The project will use:

- **Python:** Main programming language.
- **CVXPY:** Formulating and solving optimization problems.
- **NumPy:** Numerical calculations.
- **Pandas:** Dataset handling and analysis.
- **Matplotlib:** Data visualization.
- **Seaborn:** Additional visualization.
- **Google Colab:** Writing and running the code.
- **GitHub:** Project collaboration and code management.

## 5. Repository Structure

```text
Energy-Consumption-Optimization/
│
├── data/
│   └── energy_consumption.csv
│
├── project/
│   ├── part1_energy_model.ipynb
│   ├── part2_convexity.ipynb
│   ├── part3_nonconvex_model.ipynb
│   ├── part4_restore_convexity.ipynb
│   └── part5_visualization.ipynb
│
└── README.md
```

### Structure Description

- `data/`: Stores the electricity consumption dataset.
- `project/`: Contains the Jupyter Notebook for each project part.
- `README.md`: Provides an overview and description of the project.

## 6. Expected Outcome

The project aims to develop and analyze three versions of an energy optimization model:

1. Original Convex Model.
2. Modified Non-Convex Model.
3. Restored Convex Model.

The final comparison will demonstrate how mathematical modifications affect optimization problems and how convexity can be restored to obtain a suitable optimization formulation.
