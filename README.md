# CANS Risk Profile Analysis

This project analyzes how CANS (Child and Adolescent Needs and Strengths) scores relate to serious incidents among youth.

## Research Questions

- To what extent do CANS scores predict serious incidents?
- Do changes in CANS scores correlate with incident rates?
- Do specific CANS domains predict specific types of incidents?

## Approach

Instead of using traditional regression models, this project focuses on identifying **CANS risk profiles** using clustering methods.

- Use CANS domain scores as features
- Apply K-means clustering to identify youth profiles
- Compare incident rates across profiles

## Why This Matters

Understanding patterns of needs (rather than single variables) helps:

- Identify high-risk youth groups
- Inform targeted interventions
- Support decision-making for non-technical stakeholders

## Data

This project uses de-identified data from Aspiranet, including:

- CANS assessments
- Incident reports
- Demographic information

The cleaned dataset (`cleaned_data.csv`) was prepared by a team member through prior data cleaning and merging of raw CANS, incident, and demographic data.

## Project Context

This project is part of the UC Berkeley Data Discovery Program:

:contentReference[oaicite:0]{index=0}

## Author

Chunmin Zheng
UC Berkeley – Data Science & Cognitive Science
