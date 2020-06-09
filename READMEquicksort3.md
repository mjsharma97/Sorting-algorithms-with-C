# CDC
in quick sort, we use 2 fucntions. 'quicksort' to make 2 arrays on the left of pindex and 
on the right(exclusing pindex). then we continue till end>start.
other is 'partition' funtion, which takes A[end] as a pivot and put all the elements smaller than it on the left and larger on the
right by taking fixed pindex from start, increasing A[i] and compairing A[i] with pivot, if A[i] is smaller, we swap the A[pindex], A[i] abd do p++

