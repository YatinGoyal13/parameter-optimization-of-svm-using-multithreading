# Parameter Optimization of SVM

This project aims to explore the effectiveness of Support Vector Machines (SVM) in solving classification problems, with a focus on parameter optimization. In this project, we have taken the "Chess (King-Rook vs. King) Data Set" from the UCI Machine Learning Repository and created 10 random samples to train and test our SVM model. Our goal was to identify the best SVM parameters that can yield the highest accuracy for each of the 10 samples.

## Dataset

The dataset used for this project is called "Chess (King-Rook vs. King) Data Set" and is available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/chess+(king-rook+vs.+king)).

### Dataset Description

A KRK database was described by Clarke (1977). The current database was described and used for machine learning experiments in Bain (1992; 1994). It should be noted that our database is not guaranteed correct, but the class distribution is the same as Clarke's database. In (Bain 1992; 1994), the task was the classification of positions in the database as won for white in a fixed number of moves, assuming optimal play by both sides. The problem was structured into separate sub-problems by depth-of-win ordered draw, zero, one, ..., sixteen. When learning depth d, all examples at depths > d are used as negatives. Quinlan (1994) applied Foil to learn a complete and correct solution for this task.

The typical complexity of induced classifiers in this domain suggests that the task is demanding when background knowledge is restricted.

### Attribute Information

1. White King file (column)
2. White King rank (row)
3. White Rook file
4. White Rook rank
5. Black King file
6. Black King rank
7. Optimal depth-of-win for White in 0 to 16 moves, otherwise drawn {draw, zero, one, two, ..., sixteen}.

## Results

The project generated a table that shows the accuracy of each of the 10 samples, along with the best SVM parameters that yielded the highest accuracy. Here is a snapshot of the results:

![Results](https://user-images.githubusercontent.com/77913712/233218257-13cca51f-824e-4c09-a5d3-473c38826b8a.png)

## Convergence Graph

The convergence graph illustrates the progress of the optimization process. Here is a snapshot of the convergence graph:

![Convergence Graph](https://user-images.githubusercontent.com/77913712/233218344-6b6952ae-9d1c-4a39-ba9e-3c08472df5a3.png)

## Optimization using Multi-Threading

We have also implemented multi-threading to optimize the process and obtain faster results.

Feel free to explore the code and results in this repository. If you have any questions or suggestions, please don't hesitate to reach out.
