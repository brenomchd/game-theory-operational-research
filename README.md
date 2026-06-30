# Game Theory for Operational Research

Modeling and solving a competitive decision-making problem using **Game Theory** and **Linear Programming**, developed as the final project for the **Operational Research** course at the Federal University of Goiás (UFG).

The project models the competition between **Microsoft (Xbox)** and **Sony (PlayStation)** as a **zero-sum matrix game**, solved through Linear Programming. It also includes sensitivity analyses to evaluate how different consumer behavior scenarios affect the Nash equilibrium.

---

## About

This project applies concepts from **Game Theory** and **Operational Research** to analyze strategic competition in the video game console market.

The model considers two competing firms, each with four possible marketing strategies, and determines the optimal decision using mathematical optimization techniques.

The implementation was developed entirely in **Python** using **Jupyter Notebook**, combining mathematical modeling, optimization algorithms, and data visualization.

---

## Objectives

- Model a competitive market as a zero-sum game.
- Build the payoff matrix from economic assumptions.
- Solve the game using Linear Programming.
- Find the Nash Equilibrium.
- Analyze the effects of different consumer sensitivity scenarios.
- Visualize and interpret the obtained results.

---

## Problem Description

The study models the strategic competition between:

- 🎮 Microsoft (Xbox)
- 🎮 Sony (PlayStation)

Each company can choose one of four strategies:

- Reduce Price (ER)
- Maintain Price (EM)
- Raise Price (EA)
- Include Benefits (EB)

The objective is to determine the optimal strategy for each player while maximizing their expected payoff under a competitive market scenario.

---

## Methodology

The project follows the steps below:

1. Mathematical modeling of the problem.
2. Definition of players and available strategies.
3. Construction of the demand function.
4. Generation of the payoff matrix.
5. Formulation of the Linear Programming model.
6. Computation of the Nash Equilibrium using the HiGHS solver.
7. Sensitivity analysis for different consumer behavior scenarios.
8. Visualization and interpretation of the results.

---

## Main Topics

- Operational Research
- Game Theory
- Zero-Sum Games
- Nash Equilibrium
- Dominant Strategies
- Mixed Strategies
- Linear Programming
- Sensitivity Analysis

---

## Technologies

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- SciPy
- Google Colab

---

## Results

The model identifies a **pure-strategy Nash Equilibrium**, where the **Include Benefits (EB)** strategy becomes dominant for both players under the base scenario.

Additionally, the project evaluates multiple consumer sensitivity levels, showing how changes in market behavior influence strategic decisions while preserving the equilibrium under the proposed assumptions.

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/game-theory-operational-research.git
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib scipy notebook
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook located in the `notebooks/` directory and execute all cells.

---

## References

- Hillier & Lieberman — *Introduction to Operations Research*
- Hamdy A. Taha — *Operations Research*
- John Nash — *Equilibrium Points in N-Person Games*
- Von Neumann & Morgenstern — *Theory of Games and Economic Behavior*

---

## Authors

- Breno Machado Barros
- Luan de Paula Mota
- Pedro de Melo Lobo Campos
- Vitória Sofia Barbosa Pereira