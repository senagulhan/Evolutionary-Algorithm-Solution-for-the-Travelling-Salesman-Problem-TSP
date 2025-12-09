# 🧭 Solving the Travelling Salesman Problem with Evolutionary Algorithms

This project demonstrates the use of **evolutionary algorithms** to solve the **Travelling Salesman Problem (TSP)**. The implementation follows a modular approach inspired by an extensible evolutionary framework.

🛠️ **Tools & Libraries Used**  
- Python (NumPy, Matplotlib)  
- Custom evolutionary framework (`evo.py`)  
- Google Colab / Jupyter  
- Based on: [Extensible Evolutionary Algorithm](https://towardsdatascience.com/an-extensible-evolutionary-algorithm-example-in-python-7372c56a557b/)

📌 **What I Did**  
- Implemented TSP individuals in a GA-friendly format  
- Initialized a random 2D city map  
- Defined a fitness function based on total tour distance  
- Used selection, crossover (`alpha=0.5`) and mutation operations  
- Ensured a fixed starting city for all routes  
- Evolved a population of routes over multiple generations  
- Visualized the shortest route found and plotted fitness history

🧠 **Evolutionary Strategy**  
- Population Size: 100  
- Number of Offsprings: 30  
- Crossover: Order-based (`alpha=0.5`)  
- Mutation: Random swap of cities (rate = 1)  
- Epochs: 1000  
- Start City Index: 12 (kept constant in all routes)

📈 **Output & Evaluation**  
- Fitness plot showing improvement over generations  
- Visualization of the best route found  
- Printed total distance and route order

Example:
```
Best route length: 2883.23
Route order: [12 10  5 ... 31]
```

🖼️ **Visualization**  
The best route is plotted using `matplotlib`, with all cities labeled and connected in order.

🧾 **Notes**  
- Modular code structure allows easy reuse with other optimization problems  
- The evolutionary algorithm handles missing constraints like fixed starting point  
- Randomness is controlled with `np.random.seed(33)` for reproducibility

👥 **Group Members**  
- Name Surname – ID  
- Name Surname – ID  
*(Make sure all names and IDs are included exactly as on the cover page)*
