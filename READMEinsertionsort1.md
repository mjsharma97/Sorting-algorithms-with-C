# CDC
Insertion sort works like 2 sets(one sorted and other unsorted let’s say). We initially take one element in the left as already sorted, now we take the next element, replace hole with it(means we already took out), then in the left of it check if it’s smaller , if it is, we push to right by one(element on the left), again we go hole-- and check if element on left is lesser, story repeats till hole=1 and it compares with leftmost element. Now we proceed for next i, make a hole at that place and repeat

Time complexity O(n^2) space complexity O(1)
It is stable
