# API Manager Tool

## Setup

1. Ensure Python 3.8+ is installed
2. Clone or download this repository
3. Run the application:
```bash
python API_Manager.py
```

The application will automatically install required dependencies on first run.

## Manual Installation
If automatic installation fails, install dependencies manually:
```bash
pip install -r requirements.txt
```

## Requirements
- Python 3.8+
- PyQt6
- requests
- openai
- keyring

## Files
- `API_Manager.py`: Main application
- `requirements.txt`: Required dependencies
- `saved_requests.json`: Saved request configurations (created on first use)
