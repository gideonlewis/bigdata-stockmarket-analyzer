# Stock Market Analysis and Trend Prediction

This project focuses on analyzing the stock market data, particularly the Dow Jones Industrial Average (DJIA), to identify sudden price fluctuations, abnormal trading volumes, and predict trends across different timeframes (1 day, 5 days, 7 days, 1 month). The project utilizes tools like Spark, Kafka, and Airflow for data processing and workflow automation.

## Features

- Historical Data Analysis: Analyze the historical data of the DJIA to identify significant price movements, abnormal trading volumes, and other relevant patterns.
- Anomaly Detection: Utilize statistical and machine learning techniques to detect anomalies in stock prices and trading volumes.
- Trend Prediction: Develop models to predict the future trends of the stock market based on historical data and relevant indicators.
- Timeframe Analysis: Generate insights and predictions for different timeframes, including 1 day, 5 days, 7 days, and 1 month.
- Data Processing with Spark: Leverage Apache Spark for scalable and efficient processing of large volumes of stock market data.
- Streaming Data with Kafka: Integrate Apache Kafka to handle streaming data and enable real-time analysis and prediction.
- Workflow Automation with Airflow: Utilize Apache Airflow to automate data processing tasks, model training, and prediction workflows.

## Technologies Used

- **Spark**: Apache Spark is used for distributed data processing and analysis.
- **Kafka**: Apache Kafka is utilized for handling streaming data and real-time analysis.
- **Airflow**: Apache Airflow is used for workflow automation and task scheduling.
- **Python**: The primary programming language used for data processing, analysis, and modeling.
- **Machine Learning**: Various machine learning algorithms and libraries are employed for trend prediction and anomaly detection.

## Setup and Installation

To set up and run the project, follow these steps:

1. Clone the repository from GitHub:


2. Install the required dependencies and libraries:
- Set up Spark, Kafka, and Airflow according to their respective installation guides.
- Create and activate a virtual environment for the project:
  ```
  python3 -m venv myenv
  source myenv/bin/activate
  ```
- Install the necessary Python packages:
  ```
  pip install -r requirements.txt
  ```

3. Configure the project settings and parameters:
- Update the configuration files for Spark, Kafka, and Airflow according to your setup and requirements.
- Adjust the data sources, file paths, and other relevant parameters in the project code.

4. Start the data processing and analysis workflow:
- Launch the required services (Spark, Kafka, Airflow) in the appropriate order.
- Run the data ingestion and preprocessing scripts.
- Execute the analysis and prediction scripts.

5. Review the generated insights, predictions, and analysis




I follow the original repo: https://github.com/cordon-thiago/airflow-spark to set up.
I add PgAdmin to easily manage Postgresql, Kafka and Zookeeper to handle stream data.
