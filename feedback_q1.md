In the class Tester, there are following issues in the functions: 

1. def iterative_mult(w) :
* Needs to be changed to def iterative_mult(self, w)
* The for loops are incorrect. M need not be a square matrix, so you need to iterate over x and y dimensions of the matrix M. 
* The print statement is unnecessary'
* You need to return the variable you have computed at the end of the function

2. def matrix_mult(w) :
* A self parameter needs to be added (similar to point 1). 
* Unnecesary print statement
* You need to return the variable you have computed at the end of the function

3. def comparison(w) :
* iterative_mult, matrix_mult are member functions of the tester class, not the input vector w! So, inside the class you should call the functions using self.<function_name>
* Unnecessary print statements in the function

4. Plotting
* While calling member functions outside the class, the syntax is <class_object>.<function>(parameters), and self is an "automatic" parameter, so do not write that while calling the function
  
