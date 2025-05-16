# Math for AI - Machine Learning Algorithms

Group 6 - Math for AI, AI23 @ HCMUS

This repository contains implementations of various machine learning algorithms, including **Linear Regression**, **PCA&Clustering**. 
The code is designed for educational purposes, providing a clear and concise understanding of the mathematical foundations and practical applications of these algorithms.

## Contents

- **Linear Regression**: Implementation of linear regression for predictive modeling.
- **PCA&Clustering**: Implementation of PCA, KMeans and Gaussian Mixture Model (GMM) for classification tasks on Iris and ABIDE II datasets.

## Requirements

To run the code in this repository, you need the following Python libraries:
- `numpy`
- `matplotlib`
- `pandas`
- `scikit-learn` (PCA&Clustering)

Install the required libraries using:

```bash
pip install numpy matplotlib pandas scikit-learn
```

#### Set up on NixOS / Nix (if you use NixOS / Nix - else: you can skip this)
To set up a development environment using Nix, which ensures that all the necessary dependencies are available, you can use the `nix-shell` command. 
This project includes a `shell.nix` file that specifies the required packages.

1.  Ensure you have Nix installed on your system. If not, you can install it from [the official Nix website](https://nixos.org/download.html).

2.  Navigate to the project directory in your terminal:

    ```bash
    cd /path/to/Math-For-AI/
    ```

3.  Enter the Nix shell environment by running:

    ```bash
    nix-shell
    ```

    This command reads the `shell.nix` file and sets up an environment with all the specified Python packages (e.g., `jupyter`, `numpy`, `pandas`, `matplotlib`).

4.  Once inside the Nix shell, you can start Visual Studio Code:

    ```bash
    . code
    ```
    ###### Usage

    1.  Open the `.ipynb` file (Jupyter Notebook)
    2.  Choose the kernel created by `nix-shell`
    3.  Run cells
