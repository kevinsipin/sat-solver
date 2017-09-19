# sat-solver
A collection of code for scraping, formatting and solving sudokus in order to improve SAT solver performance.

This script will do three things:

1. Save 18.000+ regular and jigsaw sudokus from internet sources
2. Format the gathered html into (machine) interpretable matrices
3. Run a SAT solver (pycosat) on the two types of sudokus, for different sizes, to compare performance
