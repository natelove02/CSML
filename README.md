# Case Studies in Machine Learning (CSML)

This repository contains Jupyter notebooks and resources for the Case Studies in Machine Learning course.

## Structure
- Each notebook covers a different topic or lab, such as Numpy basics, Matplotlib plotting, and more.
- Notebooks are organized by topic and are self-contained for easy reference and study.

## Getting Started
1. Clone this repository to your local machine.
2. Set up a Python environment (recommended: Miniconda or Anaconda).
3. Install required packages (see below).
4. Open notebooks in VS Code or JupyterLab.

## Recommended Environment Setup
- Create a conda environment:
	```bash
	conda create -n csml python=3.11
	conda activate csml
	conda install jupyter numpy pandas matplotlib seaborn
	```
- Or use pip:
	```bash
	python -m venv csml-env
	source csml-env/bin/activate
	pip install jupyter numpy pandas matplotlib seaborn
	```

## Notebooks Included
- `labsetup.ipynb`: Environment setup and basic checks
- `Basic Numpy.ipynb`: Introduction to Numpy arrays and operations
- `matplotlib.ipynb`: Plotting with Matplotlib and Seaborn

## Contributing
Feel free to add new notebooks or improve existing ones. Please use clear titles and comments in your notebooks.

## License
This repository is for educational purposes.
