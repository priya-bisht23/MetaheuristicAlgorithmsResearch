# Introduction

MetaheuristicAlgorithmsResearch is a project focused on analyzing three metaheuristic optimization algorithms namely AntLion, HoneyBadger and Genetic Algorithm and then implementing the novel Hybridisation of HoneyBadger algorithm with Genetic algorithm in order to reduce the makespan time for efficient task scheduling using Jupyter Notebooks and Python. The repository includes algorithm implementations, step-by-step explanations, experimental results, and result analysis.

# Technologies Used

Programming Language: Python

Notebook Environment: Jupyter Notebook

Libraries: NumPy, Pandas, Matplotlib

Data Analysis: Excel (Experiment_Results.xlsx)

# Project Structure

ALO/ - Implementation of Ant Lion Optimizer

HBA/ - Hybrid Bat Algorithm implementation

HGA/ - Hybrid Genetic Algorithm implementation (HBA + GA)

Algorthms_Steps/ - Stepwise explanation of algorithms

Result Analysis/ - Comparative analysis and evaluation of makespan time of the three algorithms 

Experiment_Results.xlsx - Experimental results dataset of makespan time of the three algorithms varying the probability ratio (pr)  

design-specs-image/ - Reference images for algorithm designs

# Installation

Prerequisites

Ensure you have the following installed:

Python (3.x recommended)

Jupyter Notebook

Required Python libraries: NumPy, Pandas, Matplotlib

# Steps to Install and Run

Clone the Repository

git clone https://github.com/priya-bisht23/MetaheuristicAlgorithmsResearch.git

cd MetaheuristicAlgorithmsResearch

Install Dependencies

pip install -r requirements.txt

Run Jupyter Notebook

jupyter notebook

Open the relevant notebooks inside ALO/, HBA/, or HGA/ and execute them.

# Usage

Open and run Jupyter notebooks for different algorithms.

Refer to Algorthms_Steps/ for detailed execution steps.

Compare experimental results using Experiment_Results.xlsx.

Analyze algorithm performance in Result Analysis/.

# Environment Variables

If required, create a .env file for storing configurations:

DATASET_PATH=./datasets/
LOG_LEVEL=INFO

# Setup and Configuration

Modify algorithm parameters inside Jupyter Notebooks. I have performed all the experimentations varying the Probability ratio (pr) parameter for checking the makespan time. 

Ensure correct dataset paths if using external data.

Adjust visualization settings in Matplotlib if needed.

# Contributing

Fork the repository.

Create a feature branch (git checkout -b feature-name).

Commit your changes (git commit -m 'Add feature').

Push to the branch (git push origin feature-name).

Open a Pull Request.

# License

This project is licensed under the MIT License.
