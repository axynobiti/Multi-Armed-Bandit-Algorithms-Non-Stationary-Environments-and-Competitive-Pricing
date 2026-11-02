# Multi-Armed Bandits: Non-Stationary Environments & CompetitivePricing

## Part A – Non-Stationary Multi-Armed Bandits

Implementation and comparison of three bandit algorithms in a two-armed environment with periodically changing reward probabilities:

- **Upper Confidence Bound (UCB)**
- **Explore-then-Exploit (EtE)**
- **Multiplicative Weights (MW)**

Different scenarios are designed to examine how each algorithm responds to changes in the environment, with particular focus on identifying situations where MW outperforms UCB and EtE.

Performance is evaluated through cumulative rewards and arm-selection behavior, highlighting the algorithms' ability to adapt when the optimal arm changes.

## Part B – Competitive Dynamic Pricing

Application of UCB and Multiplicative Weights to a dynamic pricing problem involving two competing sellers.

A learning agent selects prices while a strategic competitor adjusts its pricing based on the learner's behavior.

The simulations examine:
- Cumulative revenue of the learner and competitor.
- Evolution of pricing decisions over time.
- Performance of UCB and MW against a best-response competitor.

## Tools

Python · NumPy · Matplotlib
