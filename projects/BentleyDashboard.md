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

## Dashboard Features

<div class="row">

<div class="col-md-6">

### 📈 Projection Models

- Freshman NCAA projections
- Career outcome predictions
- Confidence intervals

</div>

<div class="col-md-6">

### 🏒 Player Evaluation

- Historical comparables
- NCAA benchmarks
- Development curves

</div>

</div>

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

<div class="row text-center">

<div class="col-md-4">

### 20+

Junior leagues integrated

</div>

<div class="col-md-4">

### Automated

Recruiting workflows

</div>

<div class="col-md-4">

### Decision Support

Built for Division I coaches

</div>

</div>

## Live Demo

[View Bentley Hockey Dashboard](https://omuehlberg.shinyapps.io/BentleyHockey/)