# Traveling Salesman Problem Solver

A Python implementation of a solution for the Traveling Salesman Problem (TSP) using the Simulated Annealing algorithm. (Code is in french)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Traveling Salesman Problem (TSP) is a classic combinatorial optimization problem where the goal is to find the shortest possible route that visits a given set of cities and returns to the origin city.

This project implements a solution to the TSP using the Simulated Annealing algorithm, an optimization technique inspired by the annealing process of slowly cooling a material to reduce its defects.

## Features

- Solves the Traveling Salesman Problem using Simulated Annealing.
- Supports calculating distances using Haversine formula for real-world coordinates.
- Adjustable parameters like initial temperature and cooling rate for fine-tuning.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Ibayoussef123/Projet-Voyageur-de-Commerce.git
    cd traveling-salesman
    ```

2. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare your city data in a CSV file with the following format:**

    ```plaintext
     Nom Ville ,MAJ , Code Postal , Code INSEE ,Code Région, Latitude , Longitude , Eloignement 
     Machy ,MACHY ,10320,10212,21,48.133333,4.05,1.19
     Gueschart ,GUESCHART ,80150,80396,11,50.233333,2,2.18
     ...
    ```

2. **Run the jupyter notebook:**


## Contributing

Contributions are welcome! 

## License

This project is licensed under the [MIT License](LICENSE).
