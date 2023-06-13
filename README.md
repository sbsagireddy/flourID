# fluorID : Inverse design of fluorescent small molecules using deep learning

fluorID is a generative AI method for designing fluorescent small molecules that are easy to synthesize.

We use [SyntheMol](https://github.com/swansonk14/SyntheMol.git), a Monte Carlo tree search (MCTS) that explores a combinatorial chemical space consisting of molecular building blocks and chemical reactions. The MCTS is guided by a fluorescence prediction AI model, such as a graph neural network ([Chemprop](https://github.com/chemprop/chemprop)) or a random forest. Currently, SyntheMol is designed to use 137,656 building blocks and 13 chemical reactions from the [Enamine REAL Space](https://enamine.net/compound-collections/real-compounds/real-space-navigator), which can produce over 30 billion molecules.

Details for reproducing our results are provided in [fluorID.ipynb](fluorID.ipynb).

A full description of the problem and the work we completed can be found in the [project report](CS_273B_final_report.pdf).
