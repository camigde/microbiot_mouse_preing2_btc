# Jupyter Notebook Project

This README explains how to set up and run the Jupyter notebook from the command line.

## Prerequisites

- Python 3.x
- pip (Python package installer)

## Installation

1. Clone this repository:
```bash
git clone https://github.com/camigde/microbiot_mouse_preing2_btc
cd microbiot_mouse_preing2_btc
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install required libs (they are in the provided requirements.txt file)
```bash
pip install -r requirements.txt
```

4. Execute python program (in a browser with jupyter notebook or in command line)

- with command line (execute code and generate the result in a html report in current directory):
```bash
jupyter nbconvert --to html --execute projet_camille.ipynb
```
(or --to python to generate a standard python program which can be executed in command line)

- with browser (launch jupyter notebook then open manually projet_camille.ipynb, and start it from the jupyter interface):
```bash
jupyter notebook
```

