# Network Analysis and Simulation

This repository contains Python code for generating and analyzing different types of networks, including Erdös-Rényi (ER) networks and Watts-Strogatz (WS) networks.

## Introduction

The code provided in this repository aims to demonstrate the generation and analysis of ER and WS networks using Python. It includes functionalities to generate networks, plot their graphs and degree distributions, and save network information to files.

## Prerequisites

Before using this code, make sure you have the following libraries installed:

- `networkx`
- `matplotlib`
- `numpy`
- `pandas`

You can install these libraries using the following command:

```bash
pip install networkx matplotlib numpy pandas
```

## Code Explanation

The repository contains three main code sections:

1. **ER Network Generation and Analysis**
    - The code generates ER networks of different sizes and edge probabilities.
    - It plots the graphs of ER networks and their degree distributions.
    - Network information is saved to files.

2. **WS Network Generation and Analysis**
    - The code generates WS networks with different parameters.
    - It plots the graphs of WS networks and their degree distributions.
    - Network information is saved to files.

3. **Main Code Sections**
    - `generate_ER_network(N, p)`: Generates an ER network with N nodes and edge probability p.
    - `plot_network(network, title)`: Plots the graph of a network using NetworkX.
    - `plot_degree_distribution(network, title)`: Plots the degree distribution of a network.
    - `save_network_to_file(network, filename)`: Saves network information to a file.
    - `generate_WS_network(N, k, p)`: Generates a WS network with N nodes, k neighbors, and edge rewiring probability p.
    - `save_all_networks(networks_dict, prefix)`: Saves networks to files.

## Usage

1. Clone the repository to your local machine:

```bash
git clone https://github.com/4Pranjal/Network-Analysis-and-Classification.git
```

2. Navigate to the repository folder:

```bash
cd Network-Analysis-and-Classification
```

3. Run the Jupyter Notebook file `ER_WS_Network.ipynb` to execute the provided code and see the generated plots and analysis results.

## Credits

This repository is maintained by 4Pranjal. Feel free to use and modify the code for educational and research purposes.

For any questions or suggestions, you can contact me through my GitHub profile: [@4Pranjal](https://github.com/4Pranjal).
