---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Bachelor of Science in Computer Science; Bachelor of Arts in Mathematics**
  * Syracuse University, Syracuse, NY (Aug. 2024 – May 2028)
  * GPA: 3.475/4.0
  * **Relevant Coursework:** Probability Theory, Differential Equations, Applied Linear Algebra, Macroeconomics, Algorithms, Data Structures, Combinatorics, Real Analysis
  * **Awards & Leadership:** Emerging Research Fellow, Dean's List (2x), J.P. Morgan Markets Advocacy Program, Pi Kappa Alpha Founding Father, Pi Mu Epsilon Treasurer

Experience
======
* **Emerging Research Fellow – Random Matrix Theory & High-Dimensional Statistics** (May 2025 – Present)
  * Syracuse University, Department of Mathematics, Syracuse, NY
  * Investigating spectral properties of high-dimensional covariance matrices using random matrix theory; analyzing limiting eigenvalue distributions and their applications to portfolio optimization and financial risk modeling
  * Developing robust covariance estimators for high-dimensional regime where number of variables approaches number of observations; implementing shrinkage methods achieving 23% improvement in estimation accuracy for portfolio risk models
  * Applying principal component analysis and multivariate statistical techniques to extract signal from noise in large covariance structures; extending analysis to factor models and testing portfolio efficiency using modern statistical methods

* **Research Developer – GPU Computing for Gravitational Wave Detection** (Dec. 2025 – Present)
  * Syracuse University, Department of Physics, Syracuse, NY
  * Benchmarking PyCBC gravitational wave detection pipeline on Apple Silicon processors; optimizing matched-filtering algorithms and signal processing workflows for M-series GPU architecture
  * Analyzing computational performance across CPU and GPU implementations; profiling memory bandwidth utilization and parallel processing efficiency to identify optimization opportunities in scientific computing workflows

* **Software Developer Intern** (June 2025 – Aug. 2025)
  * Sponsors for Educational Opportunity (SEO), Remote
  * Developed recommendation engine using TF-IDF vectorization and collaborative filtering via SVD matrix factorization, achieving 35% increase in user engagement through personalized content delivery
  * Built full-stack web application using Flask and MySQL with RESTful API architecture; implemented user authentication, real-time feeds, and data persistence serving 500+ active users

Technical Skills
======
* **Programming Languages**
  * Python, C/C++, Java, SQL, JavaScript, R, MATLAB
* **Quantitative Libraries**
  * NumPy, Pandas, SciPy, statsmodels, scikit-learn, QuantLib
* **Tools & Platforms**
  * Git, Bloomberg Terminal, Excel/VBA, Jupyter, React, AWS, Docker

Key Projects
======
* **StatsStockX – NBA Player Securities Trading Platform** (Oct. 2025 – Present)
  * Built full-stack securities trading platform where NBA players function as tradable assets; developed quantitative pricing algorithm using time-series models achieving 78% prediction accuracy for player valuations
  * Engineered order matching engine with O(log n) complexity using red-black trees handling 100+ concurrent users; implemented WebSocket-based real-time price feeds, order book management, and multi-asset portfolio construction tools
  * Developed options trading capability with Black-Scholes pricing for calls and puts on player securities; calculated Greeks (Delta, Gamma, Theta, Vega) for hedging strategies; built portfolio analytics tracking Sharpe ratio, maximum drawdown, and 95% Value-at-Risk

* **OptiVest – Portfolio Optimization using Black-Litterman Model** (July 2025)
  * Implemented Black-Litterman model combining market equilibrium returns with investor views through Bayesian framework; integrated multi-factor stock screening across 11 sectors using quantitative signals (market cap, volatility, momentum)
  * Solved mean-variance optimization via quadratic programming with sector concentration constraints; computed efficient frontier achieving 23% improvement in risk-adjusted returns and 15% reduction in maximum drawdown relative to benchmark

* **Daily Markets Dashboard** (Feb. 2026)
  * Built real-time desktop application aggregating live market data across indices (SPY, QQQ, DIA, IWM), volatility measures (VIX, VVIX), macro indicators (10Y/2Y Treasury, DXY, crude oil), and earnings/economic calendars into a unified morning briefing tool
  * Engineered parallel data fetching pipeline achieving sub-5-second load times; implemented adaptive refresh intervals (60s during market hours, 5min premarket) and implied volatility heat map comparing current IV to 30-day averages across 10 key equities

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Research Interests
======
* **Quantitative Finance:** Portfolio optimization, risk modeling, algorithmic trading systems
* **Random Matrix Theory:** High-dimensional statistics, covariance estimation, spectral analysis
* **Scientific Computing:** GPU optimization, parallel algorithms, signal processing
* **Machine Learning:** Time-series modeling, recommendation systems, quantitative predictions
* **Financial Technology:** Trading platforms, derivatives pricing, portfolio analytics
