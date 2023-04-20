## Outreachy-Bokeh Microtask

This is a Jupyter Notebook that demonstrates how to use the Bokeh visualization library in Python to create interactive visualizations.

The notebook provides a solution to the micro-task for the project: **Create a blog post series: "Fundamentals of Data Visualization in Bokeh"**

It contains the .ipynb file created using Jupyter notebook and an accompanying images folder containing the plot images.

## Table of Contents

- <u>Installation</u>

- <u>Environment Setup</u>

- <u>Usage</u>

- <u>Project Structure</u>

### Installation

To use this notebook, you will need to have Jupyter notebook installed on your computer. You will also need to install the following Python libraries:

- Bokeh
- Pandas
- Numpy

You can install these libraries using pip:

    pip install bokeh pandas numpy

### Environment Setup

To set up the environment for this project, you can use the `environment.yml` file as follows:

1. Clone this repository to your local machine.
2. Navigate to the project directory in the terminal or command prompt.
3. Create a new conda environment using the `environment.yml` file with the following command:

    `conda env create -n <name> -f environment.yml`

replacing `<name>` with the name of your choosing. This will create a new environment with the necessary dependencies to run the project.

4. Activate the new environment using the command `conda activate <name>`.

### Usage

To use this notebook, simply open the *.ipynb* file in Jupyter Notebook and run the cells in order. The notebook contains detailed explanations of the code, including comments and markdown cells, making it easy for you to understand how the code works and how to modify it for your own purposes.

You can also view the notebook [here](https://nbviewer.org/github/Azaya89/Bokeh-microtask/blob/main/app/bokeh_micro_task.ipynb) without having to clone this repository.

### Project Structure

Here is a brief overview of the project structure:

- `app`: This directory contains the data source and python code for the task.
- `environment.yml`: This file contains the environment dependencies.
- `README.md`: This file provides an overview of the project and instructions on how to set up the environment.