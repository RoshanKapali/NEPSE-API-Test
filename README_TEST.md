# NEPSE API Test

Testing and exploring the NEPSE (Nepal Stock Exchange) unofficial API.

## About

This repository contains test implementations and experiments with the Nepal Stock Exchange unofficial API. The API allows accessing real-time market data, company information, and trading statistics.

## Installation

```bash
pip install -r requirements.txt
```

## Features

- Access to NEPSE market data
- Company information retrieval
- Real-time price and volume data
- Floorsheet data access
- Market indices and sub-indices

## Quick Start

```python
from nepse import Nepse

# Initialize the API
nepse = Nepse()
nepse.setTLSVerification(False)

# Get company list
companies = nepse.getCompanyList()
print(companies)
```

## Testing

Run the Jupyter notebook `test_nepse_api.ipynb` to see various API endpoints in action.

## Requirements

- Python 3.11+
- Flask 3.0.3
- httpx 0.27.2
- pywasm 1.2.2
- tqdm 4.66.5

## Note

This is a test repository for exploring the NEPSE API. The SSL certificate verification is disabled due to temporary issues with the NEPSE server.

## License

For educational and testing purposes only.
