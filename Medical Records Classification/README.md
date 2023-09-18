# Medical Records Classification

## Overview

This project focuses on accurately classifying medical records and documents using state-of-the-art natural language processing (NLP) models, specifically RoBERTa and LayoutLMv3. The goal is to streamline document categorization in healthcare, improving efficiency and organization.

## Table of Contents

- [Introduction](#introduction)
- [Project Details](#project-details)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In the healthcare industry, efficient categorization of medical records is crucial for quick access and effective management. This project utilizes advanced NLP techniques to classify medical records into various categories. We've employed two powerful models: RoBERTa for text classification and LayoutLMv3 for document-level classification within PDF files.

## Project Details

### Data

- The project uses a diverse dataset of medical records, encompassing various types of documents encountered in healthcare.

### Models

1. **RoBERTa Model**
   - RoBERTa is utilized for text classification within individual pages of medical records.
   - The model is fine-tuned to categorize text into predefined categories, providing granular insights into the content.

2. **LayoutLMv3 Model**
   - LayoutLMv3 is employed for document-level classification within PDF files.
   - It is equipped to identify and classify entire documents based on their content.

### Data Preparation

- The data goes through a rigorous preprocessing pipeline, including text extraction from PDFs, cleaning, tokenization, and data anonymization.

### Evaluation

- We assess model performance using standard NLP metrics such as accuracy, precision, recall, and F1-score.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/Medical-Records-Classification.git
