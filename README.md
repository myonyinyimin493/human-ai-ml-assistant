# Human-AI ML Assistant

A human-AI collaborative web app for tabular datasets that analyzes data, suggests preprocessing and modeling steps, explains why, and lets users choose what to do.

## Overview

Many beginners, students, and small business users can upload a dataset, but they do not know what to do next. They often struggle with:

- understanding dataset quality
- identifying missing values and problematic columns
- choosing preprocessing steps
- deciding whether the problem is classification or regression
- selecting suitable baseline models

This project aims to solve that problem through a human-AI collaboration workflow.

Instead of fully automating the pipeline, the system will:

1. inspect the uploaded dataset
2. summarize important findings
3. recommend the next steps
4. explain the reasoning
5. allow the user to accept, reject, or edit suggestions
6. apply approved steps
7. train baseline models
8. explain results in simple language

## Goal

Build a human-in-the-loop ML assistant for tabular datasets that helps users move from raw CSV data to informed preprocessing and baseline model training.

## Target Users

- Students learning machine learning
- Beginners with limited coding experience
- Small business users working with CSV/Excel data
- Non-experts who want guidance before training a model

## MVP Scope

The first version will support:

- CSV upload
- dataset preview
- dataset profiling
- AI-style summary of the dataset
- preprocessing suggestions
- user approval/rejection/editing of suggestions
- selected preprocessing execution
- baseline model recommendation
- model training
- results explanation

## Non-Goals for MVP

The first version will not include:

- authentication
- billing
- collaboration features
- image/audio/text datasets
- deep learning workflows
- cloud deployment
- full autonomous decision-making
- chatbot-style conversation interface
