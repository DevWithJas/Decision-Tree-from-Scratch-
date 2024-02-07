# Decision-Tree-from-Scratch-

This mini project implements a basic decision tree algorithm from scratch to predict whether to play outside based on weather conditions. It utilizes a small dataset containing information about weather conditions (sunny, rainy, windy) and corresponding temperatures, along with the decision to play outside (yes or no).

## How It's Made

- **Decision Tree Algorithm**: Implemented a basic decision tree algorithm from scratch using a recursive approach:
  - The dataset is split based on the attribute with the highest information gain.
  - This process is repeated recursively for each subset until a stopping condition is met.
  - Leaf nodes represent the decision outcomes.

- **Dataset**: Utilized a small dataset consisting of 20 samples with weather conditions, temperatures, and corresponding decisions to play outside.

- **Implementation Details**: The decision tree is represented as nested dictionaries with attributes as keys and decision outcomes as values.

