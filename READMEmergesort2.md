# CDC
In Mergesort, we use 2 functions, one to merge 2 arrays(with already assumed 2 sorted arrays)and other to break array into halves until we get only single element.

For just 2 single elements, it’s already sorted,so we simply merge

While creating a new array int B[size] in a function(NO NEED TO ALLOCATE THE MEMORY)  and you wish to copy all the contents to original array A, pass *A in the function and later A[i]=B[i] in the function using for loop.

Time complexity is O(nlogn)
space complexity is O(n) ( only go depth, and not take whole space at a time)

It is stable as If A[j]>=A[i]; B[k]=A[i]
