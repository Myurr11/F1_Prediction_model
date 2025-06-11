# F1 Race Time Prediction

![Formula 1 Logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fbrandlogos.net%2Fformula-1-logo-vector-97682.html&psig=AOvVaw00LZnx2NjJMlndtC92_NB4&ust=1749770112428000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCODVy-S_6o0DFQAAAAAdAAAAABAE)

## Project Overview

This project is a **Formula 1 race lap time and race result prediction model** built using machine learning techniques. It leverages the [FastF1](https://theoehrly.github.io/Fast-F1/) Python library to extract live and historical F1 telemetry data, combined with weather information and driver/team performance metrics.

The goal is to analyze various race and qualifying parameters, then predict race lap times and ultimately forecast race outcomes such as the winner and podium finishes.

---

## Features

- Loads and processes telemetry data from FastF1 for specific F1 race sessions.
- Integrates qualifying times, sector times, and race pace data.
- Uses live weather data from OpenWeatherMap API to factor in weather conditions.
- Incorporates team performance and historical driver position changes.
- Trains a Gradient Boosting Regressor ML model to predict lap times.
- Visualizes feature importances and relationships between variables.
- Outputs predicted race winner and top 3 podium finishers.

---

## Development Status

🚧 **Under Development** 🚧

This project is built for learning machine learning and F1 data analytics out of pure passion. As the F1 season progresses, I will add prediction files for upcoming races, refine the model, and enhance features for better accuracy.

---

## Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/Myurr11/F1_Prediction_model.git
   cd F1_Prediction_model

2. Install dependencies (preferably in a virtual environment):

   ```bash
   pip install fastf1 pandas numpy scikit-learn matplotlib requests

3. Get an API key from OpenWeatherMAp and add it to the code
