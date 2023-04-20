# F1TENTH-Intelligent-Query

This repository provides a Python script that allows you to use OpenAI to analyze and answer questions about F1TENTH simulation data.

## Installation

To get started, clone this repository and install the required packages:

```bash
git clone https://github.com/navyblue1993/F1TENTH-Intelligent-Query.git
cd F1TENTH-Intelligent-Query
pip install -r requirements.txt
```

> You'll also need an OpenAI API key to use this script. If you don't already have one, you can obtain one [here](https://platform.openai.com/account/api-keys).

## Usage

Once you have your API key, replace `"<your openai api key>"` with your actual API key in the `intelligent_query.py` script:

```python
openai.api_key = "<your openai api key>"
```

You can then test the script by running:

```bash
python intelligent_query.py
```

To use the answer_question function in your own Python code, simply import it from the intelligent_query module and pass in your question and simulation data as arguments:

```python
from intelligent_query import answer_question

question = "What is the average speed of the vehicle?"
simulation_data = "..."
answer = answer_question(question, simulation_data)
print(answer)
```

## Contributing
If you find any issues or have suggestions for improvements, feel free to submit an issue or pull request.
