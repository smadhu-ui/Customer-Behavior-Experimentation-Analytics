# Customer-Behavior-Experimentation-Analytics
Analyzing customer behavior through A/B testing and causal inference to evaluate marketing experiments and support data-driven business decisions

**Author:** Suhani Madhu, MSBA 2027, Brandeis International Business School

## Overview

This project applies experimentation and causal inference methods to marketing and product questions. It covers experiment design, A/B testing concepts, real-world case studies, causal diagrams (DAGs), and simulation-based estimation of treatment effects.

## Contents

**1. Experiment Design: Uber "Power Hour"**
Designed an experiment to test whether a driver incentive ($25 bonus for completing 5 trips within 2 hours) improves driver retention, covering the research question, hypotheses, metrics, randomization, and sample size considerations.

**2. A/B Testing Fundamentals**
Core statistical concepts behind experimentation, including the Central Limit Theorem, hypothesis testing, p-values, statistical power, and common pitfalls.

**3. A/B Testing Case Studies**
Analysis of real company experiments (such as Kiva), identifying the hypothesis, unit of analysis, stage of the consumer decision funnel, and threats to validity.

**4. Causality with DAGs**
Simulated populations for eight causal structures (mediator, confounder, collider, moderator, instrumental variable, M-bias, front-door path, and selection bias), each paired with a marketing scenario, comparing population and sample treatment effect estimates.

**5. Hotel Booking Cancellations**
Simulated a 3-million-row observational dataset to study drivers of booking cancellations (lead time, deposit, prior cancellations, special requests, daily rate), estimated effects with regression, and used repeated sampling to visualize the sampling distribution of estimates.

## Tools

Python, pandas, NumPy, statsmodels, matplotlib, Jupyter Notebook

## How to Run

1. Clone the repository
2. Install dependencies: `pip install numpy pandas statsmodels matplotlib`
3. Open `Customer_Behavior_Experimentation_Analysis.ipynb` in Jupyter and run all cells
