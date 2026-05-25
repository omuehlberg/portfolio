---
layout: project
type: project
image: img/BentleyDashboard/bentleyhockey.png
title: "Bentley Hockey Projection Dashboard"
date: 2026
published: true

labels:
  - R
  - Shiny
  - Predictive Modeling
  - Data Engineering

summary: "Interactive recruiting and player evaluation dashboard translating junior hockey performance into projected NCAA outcomes."

---

## Overview

To support Bentley Men's Hockey's Division 1 coaching staff in roster operations and recruiting, I built an interactive analytics application.

The dashboard translates player performance across 20+ junior leagues into projected NCAA outcomes using predictive modeling and historical NCAA data.

## Key Features

The application allows coaches to:
- Input player performance metrics
- Generate projected NCAA performance
- Compare players against historical benchmarks
- Visualize expected development curves

## Data Pipeline & Modeling

The project required integrating and standardizing player data across more than 20 junior leagues.

### Feature Engineering

Key variables included:

- Junior points-per-game trends
- League-adjusted scoring metrics
- Relative age
- Historical NCAA development curves
- Games played and prior season progression

### Modeling Approach

Two predictive models were developed:

**Freshman Projection Model**

- Predict first-year NCAA production

**Career Projection Model**

- Estimate long-term player outcomes

Additional components included:

- Comparable player matching
- Position-specific benchmarks
- Confidence intervals for projections

## Results

- Automated player evaluation workflows
- Reduced manual preprocessing
- Delivered decision-ready outputs for coaching staff

## Live Demo

[View Bentley Hockey Dashboard](https://omuehlberg.shinyapps.io/BentleyHockey/)