# Abstract Pandemic Agent Based Model

This repository includes a NetLogo model simulating the spread of a pandemic across a population.
The space is represented as a grid of square pixels that can be the home of an individual or a location of interest (e.g., work).
Agents represent individuals that can move through space.
Agents have one of three states:
1. Susceptable: prone to be infected
2. Infectious: can infect others in the same square pixel
3. Recovered: recovered from a previous infection and can no longer infect others

Each day, some individuals move from their initial location (home) to an area of interest. If they are infected, they leave traces in the square pixels they pass through to make their trip. These infected areas can later infect other individuals that pass through them.