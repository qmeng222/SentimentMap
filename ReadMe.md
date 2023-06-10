# SentimentMap

## About:

- Description: SentimentMap utilizes the powerful gpt-3.5-turbo model for sentiment analysis on current month's Reddit comments. With a scoring system from -1 (most negative) to 1 (most positive), it generates insightful topic-specific visualizations, offering a comprehensive overview of the sentiment landscape.
- Tech stack: GPT, Jupyter Notebook, Python, Pandas, Matplotlib, Seaborn
- Overview:
  ![sentiment map by city](/SentimentMap_res.png)

## Setup:

1. Create & activate the virtual environment (and all subsequent steps will be performed within the virtual environment):
   ```
   python -m venv env
   source env/bin/activate
   ```
2. Upgrade the pip package manager to the latest version within the current Python environment: `python -m pip install --upgrade pip`
3. Install Jupyter, and configure a kernel specifically for the virtual environment.
   - Install Jupyter in the virtual environment (so that I can use Jupyter notebooks within the virtual environment): `pip install jupyter`
   - Install ipykernel within the virtual environment (to create and manage kernels for Jupyter notebooks): `pip install ipykernel`
   - Create and install a kernel specifically for the virtual environment: `python -m ipykernel install --user --name=myenv`
4. Install packages:
   - Install the OpenAI package and the python-dotenv package:
     ```
     pip install openai
     pip install python_dotenv
     ```
     or simply `pip install openai python_dotenv` altogether!
   - Install the Python Reddit API Wrapper (PRAW): `pip install praw`
   - Install the tiktoken package to count the number of tokens: `pip install tiktoken`
   - Install the pandas package for data analysis: `pip install pandas`
   - Install the matplotlib package to plot data: `pip install matplotlib`
   - Install the seaborn package for data visualization: `pip install seaborn`
   - Install the tenacity library for retrying operations: `pip install tenacity`
   - Install the Interactive Python package: `pip install IPython`
5. Generate a snapshot of the installed packages and their versions to the requirements.txt file (or overwrite the txt file): `pip freeze > requirements.txt`, so others can install all the packages and their respective versions specified in the requirements.txt file with `pip install -r requirements.txt`

## Resources:

1. [Reddit my apps page](https://www.reddit.com/prefs/apps)
2. [Python Reddit API wrapper](https://praw.readthedocs.io/en/stable/)
3. [How to count tokens with tiktoken](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_count_tokens_with_tiktoken.ipynb)
4. [Jupyter notebook kernels: how to add, change, remove](https://queirozf.com/entries/jupyter-kernels-how-to-add-change-remove#add-virtualenv-as-python-kernel)
