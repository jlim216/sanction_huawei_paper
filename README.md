# Huawei Lobbying Analysis

This repository contains code and analysis for my undergraduate honors thesis, **"Sanctions Backfire? Corporate Political Response to National Security Restrictions in Geopolitical Rivalry"**, completed at Stanford University in May 2025. The project investigates how Huawei Technologies strategically intensified its U.S. lobbying efforts after being added to the U.S. Entity List in 2019.

Research question: **How do multinational corporations from geopolitical adversaries respond when targeted by national security sanctions?**

Based on firm-level lobbying disclosure data from [LobbyView.org](https://www.lobbyview.org/), the study employs causal inference methods to demonstrate how sanctions can unintentionally increase foreign corporate political engagement.

## Contents

### `data_analysis.ipynb`
- Main Python notebook for data cleaning, filtering, and visualizations.
- Tracks lobbying intensity, agency targeting, and issue focus before vs. after Huawei’s Entity List designation.

### `causal_impact.Rmd`
- Applies Bayesian Structural Time-Series modeling via the `CausalImpact` R package.
- Estimates Huawei’s post-sanction lobbying against a counterfactual of its pre-sanction trend.

### `difference-in-difference.Rmd`
- Implements a Difference-in-Differences (DiD) design using non-sanctioned foreign telecom firms as controls.
- Quantifies the treatment effect of Huawei’s 2019 Entity List designation.

## Data

Data is derived from U.S. Senate lobbying disclosures compiled by [LobbyView.org](https://www.lobbyview.org/). Access to the dataset is available upon request.