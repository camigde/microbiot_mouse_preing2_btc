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

3. Install required libs
```bash
pip install -r requirements.txt
```

4. Launch program
```bash
jupyter nbconvert --execute projet_camille.ipynb
```
