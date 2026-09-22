# Mathematical Modeling

Jupyter notebooks for teaching mathematical modeling — bridging math and computer science through interactive, hands-on lessons. Each notebook pairs a concept walkthrough with runnable activities and exercises.

## Notebooks

### [`numerical_approximation_taylor_rk4.ipynb`](numerical_approximation_taylor_rk4.ipynb) — Approximation Week
Why and how we approximate functions, integrals, and differential equations when exact solutions aren't available.
- Taylor Series — rebuilding functions from derivatives (`sin(x)` from scratch)
- Numerical integration — Riemann sums and the Trapezoidal rule
- Numerical ODEs — Euler's Method vs. RK4, and why RK4's error shrinks so much faster

### [`monte_carlo_stochastic_modeling.ipynb`](monte_carlo_stochastic_modeling.ipynb) — Simulation Week
Deterministic vs. stochastic models, and solving problems by simulation instead of algebra.
- Deterministic vs. stochastic modeling
- The Monte Carlo method and the Law of Large Numbers
- Activities: estimating π by random sampling, estimating dice-roll probabilities

## Setup

```bash
pip install numpy matplotlib jupyter
jupyter notebook
```

## Structure

Each notebook follows the same format: concept explanation → worked activity → discussion → key takeaways → "Try It Yourself" exercises for students to extend.
