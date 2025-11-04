# Monte Carlo Simulation for Option Pricing

This repository contains a Jupyter notebook that implements option pricing using a Monte Carlo simulation. Monte Carlo methods are widely used to estimate the fair value of financial derivatives by simulating many possible paths of the underlying asset price and computing the discounted payoff.

## Overview

The notebook (`Black_Sholes.ipynb`) demonstrates how to:

- Use geometric Brownian motion to simulate price paths of an underlying asset.
- Implement the Black‑Scholes model assumptions for option pricing.
- Estimate the price of European call and put options via Monte Carlo simulation.
- Compare simulated prices with the analytical Black‑Scholes formula.
- Experiment with varying volatility, drift, number of simulations and time steps.

This project is intended as a learning resource for understanding stochastic processes and option pricing via simulation.

## Repository structure

- `Black_Sholes.ipynb` – Jupyter notebook implementing the Monte Carlo simulation for option pricing.
- `.gitattributes` – Git attributes file (default).

## Objectives

- Illustrate Monte Carlo techniques for pricing financial derivatives.
- Provide a reproducible example of simulating asset paths and computing option payoffs.
- Offer a starting point for exploring more complex derivative pricing problems.

Feel free to extend the notebook to price other option types, add variance reduction techniques or incorporate different stochastic models.
