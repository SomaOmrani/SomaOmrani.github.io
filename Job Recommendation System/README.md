# Job Recommendation System

## Overview

This project aims to develop a Job Recommendation System that matches resumes to job descriptions (JDs) based on hard skills, soft skills, and transferable skills. The system utilizes Natural Language Processing (NLP) techniques to analyze text in job advertisements, considering a broader context than just keywords.

## Table of Contents

- [Introduction](#introduction)
- [Project Details](#project-details)
  - [Data](#data)
  - [Models](#models)
  - [Evaluation](#evaluation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Introduction

The Job Recommendation System is designed to assist recruiters, employers, and candidates in identifying suitable job matches by considering a comprehensive set of skills, including soft and transferable skills, rather than just relying on keywords. This README.md file provides an overview of the project, instructions for installation, usage, and highlights the achieved results.

## Project Details

### Data

The project relies on two datasets: `emed_careers_eu.csv` and a collection of individual HTML files containing candidate CVs. The `emed_careers_eu.csv` dataset contains job descriptions (JDs) and is used for extracting soft and hard skills. Candidate CVs are extracted from HTML files and processed for skill extraction.

### Models

The project employs the following key models:
- **BERT Model for Skill Extraction:** Named Entity Recognition (NER) using DistilBERT is used to extract soft and hard skills from text.
- **SentenceTransformer Model:** This model is used to compute semantic similarity between extracted skills from CVs and JDs for job matching.

### Evaluation

The project's evaluation focuses on achieving the following objectives:
1. Matching CV data to job descriptions based on semantic similarity.
2. Matching more than just keywords of job descriptions using NLP techniques.
3. Analyzing the text in job adverts, considering soft skills and transferable skills.

## Installation

To run this project, follow these steps:

1. Clone the repository to your local machine:
git clone https://github.com/SomaOmrani/job-recommendation-system.git
cd job-recommendation-system

2. Install the required libraries using pip:
pip install -r requirements.txt

## Usage

To use the Job Recommendation System, please follow the guidelines provided in the project's Jupyter notebooks and code files. Detailed usage instructions and examples are available within the project's documentation.

## Results

The project has achieved the following outcomes:
- Accurate matching of CVs and JDs based on semantic similarity.
- Consideration of soft skills and transferable skills, not just keywords, for job matching.
- Recognition of skills within job advertisements, enhancing the quality of candidate-employer matches.

For more details, refer to the project's specific documentation and evaluation reports.
