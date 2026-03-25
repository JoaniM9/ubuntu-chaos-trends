# Moral Landscape Analysis of South African TikTok Content

This project was developed as a final-year BSc Computer Science (Data Science) project, with a focus on analysing moral and social dynamics within South African TikTok discourse.

---

## Overview

It introduces a classification framework that categorises content into three moral dimensions:

- **Ubuntu** – community-oriented and empathetic behaviour  
- **Chaos** – disruptive, confrontational, or polarising behaviour  
- **Middle** – neutral or mixed signals  

The system combines machine learning, natural language processing, and data pipeline engineering to analyse multilingual, real-world social media data.

---

## Key Features

- End-to-end data pipeline for processing TikTok video metadata and comment threads  
- Multilingual data handling, including preprocessing and translation  
- Supervised classification using an ensemble of transformer-based models (AfroXLM-R)  
- Feature extraction incorporating sentiment, emoji usage, and conversational thread structure  
- 3D embedding and visualisation of moral dynamics using Streamlit  

---

## Technical Overview

- **Model**: AfroXLM-R (Davlan/afro-xlmr-base)  
- **Architecture**: Ensemble of three models with different seeds  
- **Classes**: Ubuntu, Middle, Chaos  
- **Performance**: Approximately 80% accuracy on a balanced dataset  
- **Approach**: Supervised learning with calibrated outputs  

---

## Repository Structure

Detailed implementation, scripts, and processing steps are available within the project directories. The codebase includes:

- Data processing and feature extraction pipelines  
- Model inference and batch prediction scripts  
- Embedding generation and 3D mapping components  
- Supporting files for model configuration and evaluation  

---

## Usage

Refer to the internal project documentation within the code directories for setup instructions, dependencies, and execution steps.
