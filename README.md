# Nano Grid Web Application
A comprehensive tool for predicting the energy output of a concept Nano Grid which leverages solar panels farm, wind turbine energy production and gauges surrounding household and EV charging station energy consumption based on various environmental and operational factors together with forecasting. This project leverages machine learning models to provide accurate predictions to aid in energy management and planning.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Run-Application](#run-application)

## Project Overview
### Objective - 1 - Wind Turbine Energy Production Prediction
### Objective - 2 - Solar Farm Energy Production Prediction
This part aims to predict the energy output of a Wind Turbine & Solar Panel Farm using historical data, panel specifications, and other relevant parameters. It provides insights that help optimize the performance and maintenance of the specific Wind Turbine & Solar Panel Farm energy systems.

#### Features
- **Energy Output Prediction**: Predicts daily and cumulative energy production.
- **Weather Data Integration**: Incorporates real-time and historical weather and specification data.
- **Model Customization**: Supports various machine learning and deep learning algorithms (GRU, LSTM).
- **Performance Metrics**: Provides detailed performance analysis with visualization.
  
### Objective - 3 - Household Power Consumption Prediction
This scenario aims to predict the energy consumption of household attached to the nano grid using historical data and other relevant parameters. It provides analytics of how electricity coming from the grid is consumed and when outages can be expected as a concept by forecasting future electricity usage and production deficit.

#### Features
- **Energy Consumption Prediction**: Predicts daily, monthly and cumulative energy consumption.
- **Model Customization**: Supports various machine learning and deep learning algorithms (LSTM).
- **Performance Metrics**: Provides detailed performance analysis with visualization.

### Objective - 4 - EV Charging Consumption Prediction
This scenario aims to predict the energy consumption of Electric Vehicals using synthesized data based on past specifications and other relevant parameters. It provides insights that help optimize the performance and maintenance of EV charging station and can be optimized as required in coming future by providing loyalty based customer discounts and further promotions.

#### Features
- **Energy Output Prediction**: Predicts daily and monthly average and cumulative energy consumption.
- **Data Integration**: Synthesized data based on past records and datasets.
- **Model Customization**: Supports various machine learning algorithms (FB Prophet).
- **Performance Metrics**: Provides detailed performance analysis and visualization.

### Objective - 5 - Chatbot Assistant
The chatbot that is build based on RAG architecture (part of advanced Machine Learning model) aims to provide solutions to the technical team regarding their prompt of issues with either the wind turbine or solar panels which they are dealing with. The provided prompt searches for the past resolutions that were made and updated for the same issue or deals with new solution findings to the error and updates accordingly.

#### Features
- **Resolution**: Provides maintenance insights based on past solutions or new researches.
- **Data Integration**: Synthesized relevant data and trained on 150,000 tokens.
- **Model Customization**: Supports various machine learning algorithms (RAG Architecture).

## Installation

Follow these steps to set up the project locally.

## Prerequisites

- Python 3.10+

## Setup
1. Download the source code zip file:
    ```bash
    https://aficorplk-my.sharepoint.com/:u:/g/personal/hasaranga_aficorp_lk/Ef44shVJEaBAhE_DkN4AklQBZVu5cb8zs5IGhOCQyf3V4Q?e=p0aXnL
    ```
2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
 
4. Run the application:
    ```bash
    python app.py
    ```
 
5. Access the application by opening `http://localhost:5000` in your web browser
 
## Run-Application
 
- Type the input as required
- Run the prediction 
- Predict Solar Energy Production, Wind Energy Production and Household Electricity Consumption Prediction as required
