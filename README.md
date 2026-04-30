# Artificial Intelligence Labs
This repository contains a collection of Jupyter Notebooks implementing various heuristic, metaheuristic, and evolutionary algorithms to solve classic optimization problems. The projects were developed as laboratory assignments.

## Repository Structure

### [Assignment 1: Local Search Algorithms](./Assignment%201.ipynb)
Focuses on solving the **0/1 Knapsack Problem** using basic local search methods.
* **Algorithms Implemented:**
  * Random Hill Climbing (RHC)
  * Steepest Ascent Hill Climbing
* **Features:** Includes solution representation, fitness function evaluation, and generation of valid solutions ensuring the maximum capacity is not exceeded. Benchmarked on various problem instances (e.g., 20 and 200 items).

### [Assignment 2: Simulated Annealing & Tabu Search](./Assignment%202.ipynb)
Expands on the optimization techniques by introducing temperature-based and memory-based metaheuristics to solve both the **Knapsack Problem** and the **Traveling Salesperson Problem (TSP)**.
* **Algorithms Implemented:**
  * Simulated Annealing (SA)
  * Tabu Search (TS)
* **Features:**
  * TSP optimization uses parametrized neighborhood generation methods (2-swap and 2-opt).
  * Extensive performance benchmarking across different hyperparameters (iterations, tabu sizes, cooling rates).

### [Assignment 3: Evolutionary Algorithms & PSO](./Assignment%203.ipynb)
Explores population-based metaheuristics for combinatorial and continuous optimization.
* **Algorithms Implemented:**
  * Evolutionary / Genetic Algorithms (EA/GA)
  * Particle Swarm Optimization (PSO)
* **Features:**
  * **Knapsack:** Binary representation with repair mechanisms for invalid solutions.
  * **TSP:** Permutation representation with specialized crossover and mutation operators.
  * **Real Coding (PSO):** Optimizing continuous functions (e.g., the Michalewicz function) using a swarm of particles with inertia and cognitive/social parameters.

### [Assignment 4: Machine Learning - Classification & Regression](./Assignment%204.ipynb)
Focuses on applying supervised machine learning techniques to solve classification and regression problems.
* **Algorithms Implemented:**
  * Decision Trees (Classifier & Regressor)
  * Random Forest (Classifier & Regressor)
  * Neural Networks (via `sklearn` and `PyTorch`)
* **Features:**
  * **Data Preprocessing:** Includes data normalization using `MinMaxScaler` and `StandardScaler`, alongside train/test data splitting.
  * **Model Evaluation:** Utilizes cross-validation and pipeline structures to track metrics like Accuracy, Precision, Recall, F1-Score, Mean Squared Error (MSE), and R2 Score.
* **Datasets:** Benchmarked on the Iris dataset for classification tasks and the Diabetes dataset for regression tasks.

## Technologies Used
* **Python 3**
* **Jupyter Notebook**
* **NumPy** (for matrix operations and random distributions)
* **scikit-learn** (for dataset loading, preprocessing, model pipelines, and evaluation metrics)
* **PyTorch** (for building, optimizing, and training custom neural networks)
* **Time & Math modules** (for performance tracking and complex function evaluation)
