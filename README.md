# parameter-optimization-of-svm
This project aims to explore the effectiveness of Support Vector Machines (SVM) in solving classification problems, with a focus on parameter optimization. In this project, we have taken a dataset and created 10 random samples to train and test our SVM model. Our goal was to identify the best SVM parameters that can yield the highest accuracy for each of the 10 samples.

The final result of our project is a table that shows the accuracy of each of the 10 samples, along with the best SVM parameters that yielded the highest accuracy. This table can be used as a reference for future classification problems that require SVM parameter optimization.

Dataset link- https://archive.ics.uci.edu/ml/machine-learning-databases/chess/king-rook-vs-king/krkopt.data

Dataset name- Chess (King-Rook vs. King) Data Set

Data set description:

A KRK database was described by Clarke (1977). The current database was described and used for machine learning experiments in Bain (1992; 1994). It should be noted that our database is not guaranteed correct, but the class distribution is the same as Clarke's database. In (Bain 1992; 1994) the task was classification of positions in the database as won for white in a fixed number of moves, assuming optimal play by both sides. The problem was structured into separate sub-problems by depth-of-win ordered draw, zero, one, ..., sixteen. When learning depth d all examples at depths > d are used as negatives. Quinlan (1994) applied Foil to learn a complete and correct solution for this task.

The typical complexity of induced classifiers in this domain suggest that the task is demanding when background knowledge is restricted.


Attribute Information:

1. White King file (column)
2. White King rank (row)
3. White Rook file
4. White Rook rank
5. Black King file
6. Black King rank
7. optimal depth-of-win for White in 0 to 16 moves, otherwise drawn {draw, zero, one, two, ..., sixteen}.

#Results

<img width="398" alt="Screenshot 2023-04-20 at 4 35 49 AM" src="https://user-images.githubusercontent.com/77913712/233218257-13cca51f-824e-4c09-a5d3-473c38826b8a.png">

#Convergence Graph

<img width="563" alt="Screenshot 2023-04-20 at 4 36 34 AM" src="https://user-images.githubusercontent.com/77913712/233218344-6b6952ae-9d1c-4a39-ba9e-3c08472df5a3.png">



