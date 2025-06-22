# 🤖 AI Traffic

## 🚦 Overview

### ☰ Table of Contents
- [Overview](#-overview)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Usage](#-usage)
- [Key-Features](#-key-features)
- [License](#-license)
- [Sales-Pitch](#-sales-pitch)


This project aims to leverage AI to analyze and predict traffic patterns, optimize bus routes, and improve overall traffic flow. It utilizes machine learning models to forecast traffic congestion and provide insights for better urban planning and transportation management.

## ⚙️ Requirements

- Python 3.13.3 or higher (https://www.python.org/downloads/)
- Google Maps API (https://developers.google.com/maps)
- Required Python packages (install using `pip install -r requirements.txt`):
  - pandas
  - scikit-learn
  - googlemaps

## 🛠️ Installation

1.  Clone the repository:

    ```bash
    git clone AI traffic
    cd AI traffic
    ```
2.  Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```
3.  Obtain a Google Maps API key and set it as an environment variable:

    ```bash
    export GOOGLE_MAPS_API_KEY="YOUR_API_KEY"
    ```

## ▶️ Usage

1.  Prepare the data:
    - Ensure the `bus_trips.csv` file is in the project directory.
    - The file should contain the necessary data for training the AI models (Source: [Specify data source if available]).

2.  Train the AI models:

    ```bash
    cd AI
    python model.py
    ```

    This script trains the machine learning models and saves them as `model1.pkl`, `model2.pkl`, and `model3.pkl`.

3.  Run the main application:

    ```bash
    python main.py
    ```

    This script uses the trained models to analyze traffic and optimize bus routes.

4.  Access the frontend:
    - Navigate to the `frontend` directory.
    - Open `index.html` in your browser or run a local server.

## ✨ Key Features

-   **Traffic Prediction:** Uses machine learning models to predict traffic congestion.
-   **Route Optimization:** Optimizes bus routes based on predicted traffic patterns.
-   **Data Analysis:** Provides insights into traffic flow and patterns.
-   **Frontend Visualization:** Visualizes traffic data and optimized routes.


## 📝 License

This project is licensed under a **Proprietary License**.

It is intended for **personal use, educational purposes, and portfolio demonstration only**.  
**Commercial use, distribution, modification, or resale is strictly prohibited without explicit written permission from the author.**

See the [LICENSE](./LICENSE) file for full license details.

## 📢 Sales Pitch

For questions and support, contact: aldinzendeli33@gmail.com

This project addresses the critical issues of traffic congestion and inefficient transportation by providing AI-driven solutions for traffic prediction and route optimization. Our key features include advanced machine learning models, real-time data analysis, and a user-friendly frontend for visualizing traffic patterns and optimized routes. The target users include urban planners, transportation authorities, and commuters seeking to improve their daily travel. Our MVP demo showcases the potential of this project to revolutionize urban transportation.
