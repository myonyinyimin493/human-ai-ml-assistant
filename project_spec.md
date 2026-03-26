
---
# Project Spec

## 1. Product Idea

A human-AI collaborative web app for tabular datasets that analyzes data, suggests the next preprocessing and modeling steps, explains why, and lets users choose what to do.

---

## 2. Target Users

### Primary users
- Students learning machine learning
- Beginners who do not know how to preprocess datasets
- Small business users working with CSV or Excel data
- Non-technical users who want guided ML support

### Initial focus
For MVP, the focus is on users who have tabular CSV data and want help understanding what to do before model training.

---

## 3. Problem Statement

Many users can upload a dataset, but they do not know what to do next.

Common problems include:
- not knowing what is wrong with the dataset
- not understanding missing values or duplicate rows
- not knowing which columns to keep or drop
- not knowing whether the task is classification or regression
- not knowing which preprocessing steps are appropriate
- not knowing which baseline models to try first

Most existing tools are either too technical, too automated, or not educational enough for beginners and small business users.

---

## 4. MVP Scope

The MVP should solve the core problem in the simplest useful way.

### MVP goal
Help users upload a CSV dataset, understand its structure and issues, review AI-generated suggestions, choose the next steps, and run baseline model training.

### Core MVP features
- CSV upload
- dataset preview
- dataset profiling
- AI-style dataset summary
- suggestion engine for preprocessing and modeling
- user accepts, rejects, or edits suggestions
- selected preprocessing steps are applied
- baseline model recommendation
- model training
- results summary and explanation

### Data type supported
- CSV only

### Task types supported
- Classification first
- Regression can be added if time allows

### Suggestion types for MVP
- missing value handling suggestions
- duplicate row detection
- possible ID-like column suggestions
- target column suggestions
- classification vs regression suggestion
- simple preprocessing recommendations
- basic model recommendations

---

## 5. Non-Goals

The following are excluded from MVP:

- authentication and user accounts
- payment or subscription system
- multi-user collaboration
- cloud deployment
- image, audio, text, or video datasets
- forecasting workflows
- deep learning model training
- fully autonomous pipeline execution without user approval
- chatbot-first interface
- advanced business dashboards

---

## 6. User Flow

### High-level flow

1. User opens the app
2. User uploads a CSV file
3. System profiles the dataset
4. System generates a summary of the dataset
5. System generates suggestions for the next steps
6. User reviews suggestions
7. User accepts, rejects, or edits suggestions
8. System applies selected preprocessing steps
9. System recommends baseline model setup
10. User confirms training
11. System trains models
12. System shows results and explanations
13. User downloads predictions or outputs
