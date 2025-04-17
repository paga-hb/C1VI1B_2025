# Data Visualization (C1VI1B) Autumn 2025

This is the repository for the Data Visualization (Autumn 2025) course at Borås University.

The course schedule can be found on [Kronox](https://schema.hb.se/setup/jsp/Schema.jsp?startDatum=2025-09-01&intervallTyp=a&intervallAntal=1&sprak=SV&sokMedAND=true&forklaringar=true&resurser=k.C1VI1B-20252-I22H5-) and the course material can be found on [Canvas](https://hb.instructure.com/courses/9397).

## Delopment Environment Setup

First, make sure you have installed Visual Studio Code, the .NET Sdk, Git, and Miniconda on your computer.

### Software

Install the following software on your computer:

- [Visual Studio Code](https://code.visualstudio.com)
- [.NET Sdk](https://dotnet.microsoft.com/en-us/download) (install .net 9.0)
- [Git](https://git-scm.com/downloads)
- [Miniconda](https://docs.anaconda.com/miniconda/install/#quick-command-line-install)

### Verify the Software Installation

Verify the software has been successfully installed, by opening a terminal and issuing the following commands (each command should print out a version):

- `code --version`
- `dotnet --version`
- `git --version`
- `conda --version`

If you don't see the print-out of a version for a specific tool, make sure the path to your tool's folder has been added to your [`PATH` environment variable](https://gist.github.com/nex3/c395b2f8fd4b02068be37c961301caa7).

### Visual Studio Code (VSCode) Extensions

Then install the necessary Visual Studio Code Extensions by executing the commands below in your terminal:

- `code --install-extension ms-dotnettools.csdevkit`
- `code --install-extension ms-dotnettools.vscodeintellicode-csharp`
- `code --install-extension ms-toolsai.jupyter`
- `code --install-extension yzhang.markdown-all-in-one`
- `code --install-extension ms-python.python`
- 
### Accounts

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

- `code -g workshop1/vscode.ipynb:0 .`

When the notebook opens in VSCode, click the text `Select Kernel` (in the top-right of the notebook), and choose `Python Environments... => conda (Python 3.12) .conda/bin/python`.

Now you can follow the instructions in the notebook.
