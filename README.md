# Experiment 2: Numerical Python
## By: Kyle Adrienne S. Hizon

In this experiment, Numerical Python will be used to calculate different matrices. Each problem will demonstrate how numpy will be used to solve computations in simple np formats efficiently.

# Instructions

## Problem 1: Normalization Problem
Normalization is one of the most basic preprocessing techniques in
data analytics. This involves centering and scaling process. Centering means subtracting the data from the
mean and scaling means dividing with its standard deviation. Mathematically, normalization can be
expressed as: Z = (matrix - mean)/standard_deviation. In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and
.std() calls. In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy

## Problem 2: Divisible by 3 Problem

Create the following 10 x 10 ndarray (From 1-100). which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy


# ----------------------Solutions------------------------

# Problem 1: Normalization Problem
Normalization is important in data analysis. Therefore, it will be used in this problem with the formula of Z = (matrix - mean)/standard_deviation. The program uses np.mean and np.std because those two functions are crucial for making an efficient program.
The array contains random numbers from 0-1 with the help of np.random.random() and then puts it inside the function wherein the Normalization computation occurs. It is then saved in a file named "X_normalized.npy" and will be loaded once the calculation is complete.
The following information will be displayed as an output: the original matrix, the mean, the standard deviation, and the normalized matrix.

Code Snippet:

![image](https://github.com/user-attachments/assets/86633479-79c3-4f1c-802a-0bbf82ec8b73)



Example Outcome:

![image](https://github.com/user-attachments/assets/da43f8e1-91b8-4f57-bce7-26dbf7b11271)



# Problem 2: Divisible by 3 Problem
This matrix uses an np.arange function that will help input the following values from 1-100 then reshaping it into a 10x10 matrix by using array.reshape(10,10) and squaring it by using the exponential syntax. Now, the matrix will be put inside the function wherein the filtering takes place. The function
will use indexing, it will index specifically the values which are divisibly by 3 using the modulus syntax. After the calculation is complete it will be saved as "div_by_3.npy". Provided is a demonstration of this result with the following display: the matrix values and the indexed values itself

Code Snippet:

![image](https://github.com/user-attachments/assets/96998891-988c-4572-a93d-a19226392589)




Result Outcome:

![image](https://github.com/user-attachments/assets/c8897e35-3787-4a71-9196-704a427fe66d)
