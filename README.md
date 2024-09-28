Median of Row Wise Sorted Matrix in Python
Here on this page, we will learn how to Find the Median of Row Wise Sorted Matrix in Python.

Example :

Input :   arr  =  [  [ 1, 3, 5 ], [ 2, 6, 9 ], [ 3, 6, 9 ]  ]
Output :   5
Median of Row Wise Sorted Matrix in Python

Algorithm
Initialize an empty array arr
Run a for loop from 0 – 3 using the variable i
Run a nested for loop from 0 – 3 using the variable j
for each iteration append matrix[i][j] element
Sort array arr
Print the fourth element of arr (it is the required solution)
Find median in a row wise sorted matrix
Python Code
Run
mat = [[1, 3, 5],
       [2, 6, 9],
       [3, 6, 9]]

arr = []

for i in range(3):
    for j in range(3):
        arr.append(mat[i][j])

arr.sort()

print("Median of the given matrix is :", arr[4])
Output
Median of the given matrix is: 5
