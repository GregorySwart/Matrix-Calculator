# Matrix-Calculator

Trying to improve my python skills by making a basic matrix calculator. I treat matrices as lists of lists, and execute operations on them by redefining each cell by using nested loops.

At the moment, the calculator can find the determinant of any 2-by-2 or 3-by-3 square matrix, add any matrices of the same dimensions, and multiply any two matrices with compatible dimensions.

My plan at the moment is to generalise the determinant-finder function and building on this also add an eigenvalue finder option, and eventually, a function that finds eigenvectors and eigenspaces too.

My main problem is that I cannot find a good way to get S(n), the group of symmetries of an n-gon, as I need to be able to get the signature of each element, as well as iterate through them to find the determinant of an n by n matrix. If I found a solution to this, I could simply define a function based on the Leibniz formula.