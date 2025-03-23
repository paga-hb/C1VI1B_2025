# Data Visualization (C1VI1B) Autumn 2025

This is the repository for the Data Visualization (Autumn 2025) course at Borås University.

The course schedule can be found on [Kronox](https://schema.hb.se/setup/jsp/Schema.jsp?startDatum=2025-09-01&intervallTyp=a&intervallAntal=1&sprak=SV&sokMedAND=true&forklaringar=true&resurser=k.C1VI1B-20252-I22H5-) and the course material can be found on [Canvas](https://hb.instructure.com/courses/9397).

## Software

Install the following software on your computer:

- [Visual Studio Code](https://code.visualstudio.com)
- [Miniconda](https://docs.anaconda.com/miniconda/install/#quick-command-line-install)
- [Git](https://git-scm.com/downloads)

## Verify the Software Installation

Verify the software has been successfully installed, by opening a terminal and issuing the following commands (each command should print out a version):

- `code --version`
- `conda --version`
- `git --version`

If you don't see the print-out of a version for a specific tool, make sure the path to your tool has been added to your `PATH` environment variable.

## Accounts

Create a GitHub account (if you don't already have one):

- Visit the [GitHub](https://github.com) web site and [Sign up](https://github.com/signup) for an account.

## Course Repository

When you have installed the software above, open a terminal and clone the GitHub repository [C1VI1B_2025](https://github.com/paga-hb/C1VI1B_2025) to your computer, and create a Python environment:

- `git clone https://github.com/paga-hb/C1VI1B_2025.git dataviz`
- `cd dataviz`
- `conda create -y -p ./.conda python=3.12`
- `conda activate ./.conda`
- `python -m pip install --upgrade pip`
- `pip install ipykernel jupyter pylance numpy pandas matplotlib seaborn plotly dash`

## Open the First Workshop Notebook

Finally, make sure you are in the `dataviz` folder in your terminal, and open the first notebook in Visual Studio Code, by issuing the command below:

- `code -g workshop1/environment.ipynb:0 .`

When the notebook opens in VSCode, click the text `Select Kernel` (in the top-right of the notebook), and choose `Python Environments... => conda (Python 3.12) .conda/bin/python`.

Now you can follow the instructions in the notebook to set up the rest of the development environment for this course.
