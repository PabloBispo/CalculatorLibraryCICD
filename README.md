# CalculatorLibraryCICD
Circle CI Test Repository

## Create Virtual Environment
    python3 -m venv ../calculator
    


## Activate Virtual Environment
    . ../calculator/bin/activate
    
## Install dependencies
    pip install -r requirements.txt

## Verify code
    flake8 --statistics

## Run Unit tests
    pytest -v --cov
