# Feed your spreadsheet to the Pandas!

_Lightning talk: FOSS4G Auckland 21/11/2025_

The Pandas library for Python streamlines data analysis by making number crunching both fast and intuitive. It excels at handling common "load-calculate-save" workflows with concise, readable code - ideal for everyday data tasks.

This ready to clone repository contains a beginner-friendly workflow using Python Notebooks and Pandas, designed for rapid experimentation and iteration, showing you how to:
 - Load datasets
 - Filter and transform data
 - Perform basic calculations
 - Plot outputs
 - Export results


## Note

There are a **lot** of ways to install Python, manage packages, run analyses and interact with Notebooks. Advanced users can take these recommendations with a hefty grain of salt - this repository outlines a simple and stable flow that should be easy for Python or Pandas beginners to get started with.

IPython Notebooks provide a visual interactive means of running Python scripts and immediately viewing the output. This is very handy in some situations and not useful or appropriate in other contexts. To develop complex flows I often find myself developing the core functionality against a test dataset in a Notebook and then copying the functional code to a script for the "real" runs.


## Prerequisites

 - [Python](https://www.python.org/) (version 3.13 recommended as of November 2025) installed and accessible from CLI as `python`, `python3` or `python3.13`, depending on your system (referred to as `<python>` below)
 - [VS Code](https://code.visualstudio.com/download) editor with **Python** and **Jupyter** extensions installed


## Running

1. clone this repository (if using Git) or "Download ZIP" from GitHub
1. navigate a command prompt or terminal to the folder containing this readme
1. use your system Python to create a virtual environment in a new `.venv` folder: `<python> -m venv .venv`
1. activate the virtual environment:
    - Linux/macOS (bash/zsh): `source .venv/bin/activate`
    - Windows cmd.exe: `.venv\Scripts\activate.bat`
    - Windows PowerShell: `.venv\Scripts\Activate.ps1`
    - See the documentation for other configurations: https://docs.python.org/3/library/venv.html#how-venvs-work
1. install dependencies: `pip install -r requirements.txt`, which will install:
    - `ipykernel` Python Notebooks functionality
    - `matplotlib` plotting/charting
    - `openpyxl` read/write Excel
    - `pandas` data analysis library
1. open this folder in VS Code
1. in VS Code open the `example.ipynb` file
1. use the run buttons to run specific cells or the entire Notebook
