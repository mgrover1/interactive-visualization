<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Interactive Visualization Cookbook

[![nightly-build](https://github.com/mgrover1/interactive-visualization-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/mgrover1/interactive-visualization-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](http://binder.mypythia.org/badge_logo.svg)](http://binder.mypythia.org/v2/gh/mgrover1/interactive-visualization-cookbook/main?labpath=notebooks)

## Motivation

This cookbook walks through how to visualize your geoscience data interactively using python! We walk through tabular and gridded visualizations, focusing on how to get started to building more complex dashboards for your data.

## Authors

[Max Grover](@mgrover1)

### Contributors

<a href="https://github.com/mgrover1/interactive-visualization-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=mgrover1/interactive-visualization-cookbook" />
</a>

## Structure
(State one or more sections that will comprise the notebook. E.g., *This cookbook is broken up into two main sections - "Foundations" and "Example Workflows."* Then, describe each section below.)

### Foundations
This section will break down the different options within the python interactive visualization space. This includes
- Holoviz Stack
- Panel
- Plotly

### Example Workflows
Here we apply the foundations to real-world datasets such as
- Weather radar maps
- Large cloud-hosted datasets
- Tabular climate datasets

## Running the Notebooks
You can either run the notebook using [Binder](https://mybinder.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://mybinder.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)   

1. Clone the `https://github.com/mgrover1/interactive-visualization-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
    ```  
1. Move into the `interactive-visualization-cookbook` directory
    ```bash
    cd cookbook-example
    ```  
1. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate interactive-visualization-cookbook-dev
    ```  
1.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
