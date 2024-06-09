# Numerical Experiments in Convex Optimization

This repository contains the Jupyter Notebook for the numerical experiments presented in the report titled **"Optimization of High-Dimensional Convex Functions"**. The notebook includes interactive implementations of various optimization algorithms and applications, allowing users to explore and reproduce the experiments described in the report.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Experiments Included](#experiments-included)

## Introduction

This project focuses on the optimization of high-dimensional convex functions, particularly those that are composite functions combining differentiable and non-differentiable components. The Jupyter Notebook in this repository includes interactive interfaces for various numerical experiments conducted during the project.

## Installation

To run the notebook, you will need to have Python and Jupyter installed. Follow these steps to set up the environment:

1. Clone this repository:
    ```sh
    git clone https://github.com/bjmxr/convex-optimization-experiments.git
    cd convex-optimization-experiments
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

## Usage

Open the notebook `Optimization_Experiments.ipynb` in Jupyter and follow the instructions provided in each section. The notebook contains explanations and code cells that you can execute interactively to understand and reproduce the numerical experiments.

## Experiments Included

The following experiments are included in the notebook:


1. **Image Fusion**: Techniques for combining multiple images into one.
2. **Total Variation Denoising**: Image denoising using the total variation norm.
3. **Compressive Sensing**: Signal reconstruction from incomplete data.


