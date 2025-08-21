
Knapsack Optimization Algorithms 🚀

This project compares Dynamic Programming (DP) with metaheuristic optimization techniques like Genetic Algorithm (GA), Particle Swarm Optimization (PSO), and Simulated Annealing (SA) for solving the 0/1 Knapsack Problem.

It includes:

📂 Dataset (data.csv) with randomly generated weights & values

⚙️ Implementations of DP, GA, PSO, SA

📊 Performance comparison (time complexity & solution quality)

📈 Visualizations with Matplotlib

📌 Problem Statement

The 0/1 Knapsack Problem:

Given n items with weights and values, and a knapsack capacity W, select items to maximize value without exceeding capacity.

This project evaluates different approaches in terms of efficiency and accuracy.

🔑 Features

Dynamic Programming (DP) → Optimal baseline solution

Greedy (optional, if you want to mention) → Fast heuristic

Genetic Algorithm (GA) → Evolution-inspired optimization

Particle Swarm Optimization (PSO) → Swarm intelligence based search

Simulated Annealing (SA) → Probabilistic hill-climbing

📂 Project Structure
├── data.csv              # Dataset (values & weights)
├── knapsack.ipynb        # Jupyter Notebook implementation
├── ot_model.ipynb        # (Optional additional experiments)
├── README.md             # Project documentation

📊 Results

Time Complexity:
DP grows exponentially with problem size, while GA/PSO/SA scale better.

Solution Quality:
GA, PSO, SA achieve >90% of optimal DP value in most runs.

📈 Example visualization:

Execution Time vs Problem Size

Solution Quality (% of DP)
