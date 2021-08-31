# Machine Learning POC

This was developed with Python 3.9, but other versions will likely work

## Setup

1. Download the data file and place it into the `poc` directory. Example:
    ```shell
    curl https://www2.census.gov/programs-surveys/demo/datasets/income-poverty/time-series/data-extracts/2017/cps-asec-research-file/pppub17.csv -o poc/pppub17.csv
    ```
2. Create a virtual environment in your preferred way and install the requirements. Example:
   ```shell
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. Run the Jupyter server in your preferred way. I like to use [https://www.jetbrains.com/help/pycharm/jupyter-notebook-support.html](PyCharm)
