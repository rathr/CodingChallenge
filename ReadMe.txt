Challenge Feature 1:
1.	I would import the text file as Dec converted from ASCII text (Char to Dec) (matrixA)
2.	I would create a new matrix (Matrix1) that would sum the decimals, delimited by the Space 
Character Dec
3.	I would then go through Matrix1 and search for unique/non-unique sums and count how many 
times that sum shows up and output that into a new three column matrix (Matrix2) with 
column:
A.	 Containing the sum
B.	A count of the number of space characters before that sum
C.	The number of times that sum has appeared
4.	I would create a 3 column output matrix(Matrix3) that: 
A.	Creates a clone of column 1 from Matrix2
B.	Finds the position of the sum from matrixA (skips up to the number of space characters 
from column 2 in Matrix2 on that line and converts Dec back to ASCII up to the next 
space character Dec and stops) 
C.	 Creates a clone of column 3 from Matrix2
i.	If the sum has already been found, it skips that sum and goes to the next sum
5.	Finally, I have columns Matrix3 sorted by the value in column A and output the values from 
columns B and C

Challenge Feature 2:
1.	Using the existing Matrix3, I would count the number of unique sums for each 'tweet' (line) and 
output into Matrix4
2.	I would then have a regressional equation that adds to Matrix 4 following the equation:
Sum of total current values in Matrix4/number of total values in Matrix4
3.	I would output Matrix4 each time a new tweet is added to the input file 
