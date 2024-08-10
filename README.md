# Mobile Price Range Prediction

## Project Overview

This project aims to predict the price range of mobile phones based on their specifications using machine learning techniques. The dataset contains information on various features like battery power, clock speed, RAM, and more. By leveraging this data, we build and evaluate several classification models to categorize mobile phones into distinct price ranges.

## Dataset

The dataset consists of 2,000 entries with 21 features, including:

- `battery_power`: Battery power in mAh
- `clock_speed`: Processor speed in GHz
- `ram`: Random Access Memory in MB
- `px_height` and `px_width`: Pixel resolution height and width
- `mobile_wt`: Weight of the mobile phone in grams
- `price_range`: Target variable with four possible price categories (0: low cost, 1: medium cost, 2: high cost, 3: very high cost)

## Project Structure

- `MACHINE LEARNING CA2 .ipynb`: The Jupyter Notebook containing the entire analysis, including data exploration, feature engineering, model building, and evaluation.

## Installation

To run this project, you need to have Python installed along with the following libraries:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
