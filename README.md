# 🚚 Multi-Depot VRP Optimizer & Logistics DSS

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Operations Research](https://img.shields.io/badge/Operations_Research-Logistics_Optimization-10b981?style=for-the-badge)
![Algorithms](https://img.shields.io/badge/Heuristics-2--Opt_Local_Search-fbbf24?style=for-the-badge)

The **Multi-Depot VRP Optimizer** is an interactive Decision Support System (DSS) designed for supply chain and logistics management. It solves the complex Multi-Depot Vehicle Routing Problem (MDVRP) by clustering customers to their nearest distribution centers and optimizing each route using heuristic algorithms.

🔗 **[Explore Live Simulation (Live Demo)](https://onurfgg.github.io/multi-depot-vrp-optimizer)**

## 📊 Mathematical Model & Algorithms

This tool does not rely on third-party routing APIs; it is built entirely on custom mathematical models in JavaScript. The engine processes the network in three phases:

1. **Clustering (Distance-Based):** The algorithm scans the Cartesian plane and assigns every customer node to its nearest depot node using Euclidean distance calculations.
2. **Initial Routing (Nearest Neighbor):** For each isolated cluster, the system quickly constructs an initial, feasible route by continuously navigating to the nearest unvisited node.
3. **Local Search Optimization (2-Opt Heuristic):** The system detects intersecting (crossed) routes and systematically swaps edges (`twoOptSwap`) to untangle the graph. This iterative improvement minimizes the total travel distance until a local optimum is reached.

## 🌟 Highlighted Features

* **Multi-Depot Support:** Users can place multiple depots on the map. The system intelligently partitions the workload among available distribution centers.
* **Cartesian Grid & Visualizer:** A built-in custom `<canvas>` engine renders the nodes on a scaled coordinate grid, simulating a real-world geographic distribution.
* **Dynamic Cost Function ($Z$):** Users can input custom transportation unit costs. The system calculates the estimated total transportation cost in real-time.
* **Algorithm Savings Metric:** The dashboard displays the exact percentage of distance saved by the 2-Opt algorithm compared to the initial Nearest Neighbor route.
* **Live Animation:** The pathfinding process is visually animated, allowing users to watch the routes being constructed and optimized dynamically.

## ⚙️ Installation and Usage

The application is a 100% client-side web tool. No backend configuration is needed.

1. Clone the repository:
   ```bash
   git clone [https://github.com/onurfgg/BU_KISMA_REPO_ADINI_YAZ.git](https://github.com/onurfgg/multi-depot-vrp-optimizer.git)


   Onur Furkan Gök

[Linkedin](https://www.linkedin.com/in/onurfurkan/) 
[GitHub](https://github.com/onurfgg) 
