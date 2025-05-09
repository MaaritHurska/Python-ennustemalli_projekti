# Cash Flow Forecast Demo using OpenAI API and Python

This repository demonstrates how to use the OpenAI API with Python to forecast future cash flows based on historical data.

## Project Structure

```
.
├── README.md
├── requirements.txt
├── cashflow_forecast.py
├── sample_data.csv
└── LICENSE
```

## Prerequisites

* Python 3.8+
* An OpenAI API key

## Installation

```bash
git clone https://github.com/yourusername/cashflow-forecast-demo.git
cd cashflow-forecast-demo
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

```bash
export OPENAI_API_KEY=your_api_key
python cashflow_forecast.py --input sample_data.csv --months 6
```

## sample\_data.csv

```csv
date,amount
2024-01-01,1000
2024-02-01,1200
2024-03-01,1100
2024-04-01,1300
2024-05-01,1250
```


## requirements.txt

```text
openai
pandas
python-dotenv
```


## License

This project is licensed under the MIT License.
