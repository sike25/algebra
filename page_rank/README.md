## Page Rank Lab

### Overview
This Mathematica project explores the application of Markov chains to model web surfing behavior and the calculation of PageRank, which is central to Google's search algorithms. The exercise employs matrix operations and eigenvector calculations to determine the probability distribution of a web surfer's location on a simplified internet graph over time.

###  Features
We set up a basic Markov chain to model initial states and transition probabilities based on hypothetical web page links. Then we use matrix multiplication, power iteration and eigen analysis to find the steady state probability vector which holds the page ranks for each web page.

### Example Commands
```mathematica
(* Define the initial state vector *)
initialState = {0.25, 0.25, 0.25, 0.25};

(* Calculate the probability vector after three transitions *)
probVector = MatrixPower[transitionMatrix, 3].initialState;

(* Find eigenvalues and eigenvectors for the transition matrix *)
eigenValues = Eigenvalues[transitionMatrix];
eigenVectors = Eigenvectors[transitionMatrix];
```
### License
Open-source and available for educational use.
