# ECE2112---Experiment-2

This project contains two Python problems implemented using NumPy in Jupyter Notebook format. Below is a description of each problem.

## Requirements

- Python 3.12+
- NumPy

## Files

- `Experiment 2.ipynb`: The Jupyter Notebook containing the code for the two problems.
- `X_normalized.npy`: A NumPy array file generated during the normalization problem.
- `div_by_3.npy`: A NumPy array file containing elements divisible by 3 from the second problem.

## Problem 1: Normalization Problem

This problem generates a random 5x5 matrix of values from a normal distribution, then normalizes the matrix using the formula:

[ X_normalized = X - meanstd_dev ]

### Steps:

1. Create a 5x5 matrix `X` using random values.
2. Calculate the mean and standard deviation of `X`.
3. Normalize the matrix.
4. Save the normalized matrix as `X_normalized.npy`.

### Output:

- The original matrix `X`.
- The normalized matrix `X_normalized`.

## Problem 2: Divisible by 3 Problem

This problem creates a matrix of squared integers from 1 to 100 and extracts the elements that are divisible by 3.

### Steps:

1. Create an array of integers from 1 to 100.
2. Square the integers.
3. Reshape the squared values into a 10x10 matrix.
4. Extract elements divisible by 3.
5. Save the elements divisible by 3 as `div_by_3.npy`.

### Output:

- A list of squared integers divisible by 3.

## How to Run

1. Install dependencies:
   ```bash
   pip install numpy
   ```
   
2. Open the notebook `Experiment 2.ipynb` in Jupyter or execute the Python code in a compatible environment.

3. Run each cell to see the output and generate the `.npy` files.

