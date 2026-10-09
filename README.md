# Study Assistant — starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Step 1: Clone the repository
git clone <repository-url>
cd assistant-teamNN

Replace <repository-url> with the URL of this repository.

Step 2: Create a virtual environment
python -m venv .venv
Step 3: Activate the virtual environment

On Windows:

.venv\Scripts\activate

On macOS or Linux:

source .venv/bin/activate
Step 4: Install dependencies
python -m pip install -r requirements.txt
Step 5: Check the environment
python scripts/check_env.py

Follow any error messages if the environment check fails.

## Run

python -m pytest

## Test

nguyenngocanhduong 1108

## Project structure

assistant-teamNN/ 
├── README.md 
├── .gitignore 
├── requirements.txt 
├── pyproject.toml 
├── src/ │ 
  └── assistant/ 
├── ui/ │ 
  └── README.md 
├── data/ │ 
├── README.md │ 
  └── offices.csv 
├── tests/ 
├── docs/ │ 
├── README.md │ 
  └── team.md 
  └── scripts/ 
  └── check_env.py
