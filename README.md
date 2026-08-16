# Quantitative-Research

## Probability Theory & Measure Theory
1. Fubini's theorem
2. Tonelli's theorem
3. Radon–Nikodym theorem
4. Doob’s martingale convergence theorems
5. Ergodic theory
6. Large deviations principle
7. Stochastic dominance

## Signal Processing & Transformations
1. Fourier Transform
2. Discrete Fourier Transform (DFT)
3. Wavelet
4. Short-Time Fourier Transform (STFT)
5. Spectral density
6. Kosambi–Karhunen–Loève theorem
7. Wigner-Ville distribution
8. Hilbert–Huang Transform (HHT)
9. Independent Component Analysis (ICA)
10. Singular Spectrum Analysis (SSA)

## Simulation & Numerical Methods
1. Inverse Transform Algorithm
2. Pseudo-random number generation (e.g., Mersenne Twister, Box–Muller transform)
3. Monte Carlo method
4. Variance reduction techniques (e.g., antithetic variates, importance sampling, control variates)
5. Quasi-Monte Carlo methods (e.g., Sobol sequences, Latin hypercube sampling)
6. Markov Chain Monte Carlo (MCMC) (e.g., Metropolis-Hastings, Gibbs sampling)
7. Particle filtering (for sequential Monte Carlo)
8. Finite difference methods
9. Kalman filter

## Statistical Inference & Estimation
1. Confidence intervals
2. Hypothesis testing (e.g., t-tests, ANOVA)
3. Non-parametric tests (e.g., Wilcoxon, Kruskal-Wallis)
4. Central Limit Theorem
5. Law of total expectation
6. Maximum Likelihood Estimation (MLE)
7. Kernel density estimation
8. Bootstrapping
9. Empirical likelihood
10. Information criteria (e.g., AIC, BIC)
11. Bayesian inference (e.g., MCMC, Bayesian networks)
12. Statistical inference
13. Gaussian process
14. Cross-entropy
15. Kullback–Leibler (KL) divergence
16. Chi distribution
17. Chi-squared divergence
18. Cohen's kappa
19. Shapley values

## Stochastic Processes & Random Motion
1. Brownian motion
2. Arithmetic Brownian Motion (ABM) and Geometric Brownian Motion (GBM)
3. Correlated Brownian motion
4. Poisson point process
5. Fractional Brownian motion
6. Itô integral
7. Itô's lemma
8. Martingale Probability theory
9. Chapman-Kolmogorov equation
10. Ornstein–Uhlenbeck process
11. Lévy processes
12. Bessel process
13. Local time
14. Stochastic calculus (Stratonovich integral, quadratic variation)
15. Diffusion processes (Fokker–Planck equation)
16. Jump-diffusion models (e.g., Merton model)
17. Hawkes process
18. Volterra process
19. Stochastic Volterra equations/integral equations
20. Stochastic partial differential equations (SPDEs)
21. Dynkin π-λ theorem
22. Lebesgue–Stieltjes integration
23. Markovian lifting
24. Harnack inequality / Log-Harnack inequality
25. Carathéodory extension theorem
26. Monotone class theorem

## Time Series Analysis
1. Autocovariance and Autocorrelation
2. Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF)
3. Stationarity
4. Unit root
5. Linear regression
6. Autoregressive (AR) and Moving Average (MA) models
7. Autoregressive Moving Average (ARMA) model
8. Yule-Walker equations
9. Levinson–Durbin algorithm
10. Autoregressive Integrated Moving Average (ARIMA) and Seasonal ARIMA (SARIMA)
11. Exponential smoothing (e.g., Holt-Winters method)
12. Periodic processes and Discrete Fourier Transform (DFT)
13. Spectral density
14. Vector Autoregression (VAR)
15. Cointegration
16. Granger causality
17. Structural break tests (e.g., Chow test, Bai-Perron test)
18. Long memory processes (e.g., ARFIMA, fractional integration)
19. GARCH (Generalized Autoregressive Conditional Heteroskedasticity)
20. ARCH (Autoregressive Conditional Heteroskedasticity)
21. GARCH extensions (e.g., EGARCH, GJR-GARCH)
22. Interrupted Time Series Analysis (ITS)
23. Backtesting
24. State-space models
25. Hidden Markov Model (HMM)
26. Markov switching model

---

### Foundational Probability & Stochastic Processes
1. Poisson Random Measure — Generalization of Poisson processes to arbitrary spaces (prerequisite for Cox Process and Queueing Theory). 
2. Queueing Theory — M/M/1, M/G/1 queues built on Poisson arrivals (applies Poisson processes). 
3. Cox Process (Doubly Stochastic Poisson) — λ(t) is itself random (extends Poisson processes).

### Brownian Motion & Extensions
1. Stochastic Differential Equations (SDEs) — General theory and existence/uniqueness (core for all stochastic calculus).
2. Cox-Ingersoll-Ross (CIR) — Mean-reverting process that stays positive (special case of SDEs, often used in finance). 
3. Bessel Bridge — Bridge that stays positive (for interest rates, related to CIR and SDEs).
4. Brownian Sheet — 2D generalization (bridge on a rectangle, extends Brownian motion concepts).

### Fractional & Long-Memory Processes
1. Fractional Brownian Bridge — fBM conditioned to return to zero (requires understanding of fractional Brownian motion).
2. Fractional Ornstein-Uhlenbeck — Mean-reverting fBM (builds on fractional Brownian motion).
3. Multifractional BM — H varies with time H(t) (generalization of fractional BM).
4. Wavelet-based Hurst estimation — More robust than R/S analysis (applies to fractional processes like fBM).

### Advanced Stochastic Calculus
1. Girsanov Theorem — Change of measure in stochastic calculus (requires SDEs and measure theory). 
2. Feynman-Kac Formula — Link between PDEs and SDE expectations (uses SDEs and measure changes). 
3. Malliavin Calculus — Differentiation of random variables (advanced, builds on SDEs and stochastic calculus).

### Rough Paths & Volatility Modeling
1. Rough Path Theory — Beyond Itô for H < 0.5 (extends stochastic calculus to rough paths).
2. Rough Heston Model — fBM-driven volatility with H ≈ 0.1 (applies rough path theory and fractional processes).

### Applications in Finance
1. Stochastic Control — Hamilton-Jacobi-Bellman equations (advanced, uses SDEs and control theory). 
2. Monte Carlo Basket Options — Price options on correlated assets (applies SDEs, stochastic calculus, and simulation techniques).
