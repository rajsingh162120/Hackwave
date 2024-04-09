
# Power Grid Stability Prediction

This repository addresses the problem statement of predicting total power generation, distributing generated power to consumption nodes, and determining the stability of the power grid. The project includes data integration, predictive modeling, and analysis to achieve these objectives.

## Problem Statement Overview

1. **Power Generation Prediction**: Predict total power generated (p) for the first 3 months of 2024 at an hourly granularity using past 5 years of data.
2. **Data Integration**: Merge all 20 files of data to create a final input file consisting of Date time, Air, Pressure, wind speed, and Power generated variables.
3. **Power Distribution**: Distribute the generated power to 3 different consumption nodes (refer the 4-Node Star Architecture) according to specified percentages.
4. **Grid Stability Prediction**: Determine the stability of the power grid using the existing and newly prepared dataset. The stability is the dependent variable.
5. **Analysis and Reporting**: Analyze the stability trends over the span of three months and identify patterns in unstable conditions. Present insights to inform grid operators about potential vulnerabilities and proactive measures.

## Features

- **Data Integration**: Merges 20 files of data to create a comprehensive dataset.
- **Predictive Modeling**: Utilizes machine learning algorithms for power generation prediction and grid stability prediction.
- **Power Distribution**: Allocates generated power to consumption nodes based on specified percentages.
- **Analysis and Reporting**: Analyzes stability trends and presents insights to inform grid operators.

## How to Use

1. **Clone Repository**: Clone this repository to your local machine.
2. **Install Dependencies**: Install the required dependencies listed in `requirements.txt`.
3. **Data Integration**: Merge all 20 files of data into a final input file.
4. **Model Training**: Train machine learning models for power generation prediction and grid stability prediction using the merged dataset.
5. **Power Distribution**: Distribute the predicted power to consumption nodes according to specified percentages.
6. **Stability Analysis**: Analyze stability trends over the specified time period and identify patterns in unstable conditions.
7. **Reporting**: Present insights and findings in a comprehensive report format.

## Dataset

- **20 Files of Data**: Contains data related to Date time, Air, Pressure, wind speed, and Power generated variables.
- **Grid Folder Data**: Includes price per unit, unit consumption, and grid stability report on an hourly basis.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn

## Contribution

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to make any adjustments or additions as needed, and let me know if there's anything else you'd like to include!
