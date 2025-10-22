# Kelly Criterion Simulator

This project demonstrates the **Kelly Criterion**, a fundamental concept in quantitative finance and gambling theory. It determines the optimal fraction of capital to risk on a bet (or trade) to maximize long-term exponential growth.

---

## 🧠 Theory

If a game (or trade) has:
- Win probability **p**
- Loss probability **1 − p**
- Payoff ratio **b** (you win *b* times your bet if successful)

Then the **expected log growth** is:

\[
g(f) = p \ln(1 + f b) + (1 - p) \ln(1 - f)
\]

Maximizing this with respect to **f** gives the optimal bet fraction:

\[
f^* = \frac{p(b + 1) - 1}{b}
\]

The Kelly fraction maximizes long-term growth, balancing reward and risk.

---

## ⚙️ Setup and Execution

### 1. Clone and enter the project

```bash
git clone <your-repo-url>
cd kelly-criterion
