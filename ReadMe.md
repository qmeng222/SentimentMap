# SentimentMap

## Overview:

- About: a movie plot generator (generates a movie plot description based on seed input) and content-based movie recommender

## Setup:

1. create & activate the virtual environment (and all subsequent steps will be performed within the virtual environment):
   ```
   python -m venv env
   source env/bin/activate
   ```
2. upgrade the pip package manager to the latest version within the current Python environment: `python -m pip install --upgrade pip`
3. install the OpenAI package and the python-dotenv package:
   ```
   pip install openai
   pip install python_dotenv
   ```
   or simply `pip install openai python_dotenv` altogether!
4. install the Python Reddit API wrapper called "praw": `pip install praw`
5. install the tiktoken package to count the number of tokens: `pip install tiktoken`
6. install the pandas package for data analysis: `pip install pandas`
7. install the seaborn package for data visualization: `pip install seaborn`
8. install the matplotlib package to plot data: `pip install matplotlib`
9. install the tenacity library for retrying operations: `pip install tenacity`
10. install the Interactive Python package: `pip install IPython`
11. generate a snapshot of the installed packages and their versions to the requirements.txt file (or overwrite the txt file): `pip freeze > requirements.txt`, so others can install all the packages and their respective versions specified in the file with `pip install -r requirements.txt`

## Resources:

1. Reddit my apps page: https://www.reddit.com/prefs/apps
2. Python Reddit API wrapper: https://praw.readthedocs.io/en/stable/
3.
