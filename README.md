What is our problem?

The primary objectives of this program are to investigate three key aspects of percolation:
1. Path Existence Check (The Burning Method): Our first goal is to determine the probability P_flow that a path connecting the first and last rows exists as a function of the occupancy probability p. The Burning Method is employed to check for the existence of such paths, ensuring efficient and accurate results
2. Maximum Cluster Size (s_max): We aim to compute the average size of the maximum cluster, denoted as ⟨s_max⟩, as a function of the site occupancy probability p. This metric provides insights into the largest connected structure within the lattice, shedding light on percolation phenomena
3. Cluster Size Distribution (n(s, p, L)): Utilizing the Hoshen-Kopelman (HK) algorithm, clusters are identified within the lattice. We then analyze the distribution of cluster sizes, denoted as n(s, p, L), for a given probability p. This distribution provides a detailed characterization of the spatial arrangement of occupied sites within the lattice.

The implementation of these Monte Carlo simulations involves conducting T trials to generate comprehensive output files. Through these simulations, we aim to gain a deeper understanding of the percolation behavior on the square lattice and observe how various parameters, such as path existence, maximum cluster size, and cluster distribution, evolve with changing probabilities of site occupancy.


Methodology

The simulation was performed using:

1. Language: Python.
2. In Colab Notebook with the newest version of Python (3.12).
3. Computer used for performing simulations was Google servers and 16GB RAM with processor Radeon 5.
4. To create a single output file of type it took all around 1 hour. ′Ave−L ′ + L +′ T ′ + T +′ .txt′ for L = 10, 50, 100 and T = 1000 or  T=10000.

