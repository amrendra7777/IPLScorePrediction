# IPL Score Prediction Model

This project aims to predict IPL match scores based on team and captain information using machine learning.

## Project Structure
- `data/`: Contains IPL match data
- `src/`: Source code files
  - `data_collection.py`: Script to collect IPL match data
  - `preprocessing.py`: Data preprocessing utilities
  - `model.py`: Machine learning model implementation
  - `app.py`: Streamlit web interface

## Setup
1. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run src/app.py
```

## Features
- Predict IPL match scores based on:
  - Team names
  - Team captains
  - Venue information
  - Historical performance