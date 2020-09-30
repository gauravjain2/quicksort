## SORTING NUMBER 1 : QUICKSORT

### What is Quick Sort ?
Quicksort partitions an array and then calls itself recursively twice to sort the two resulting subarrays. This algorithm is quite efficient for large-sized data sets as its average and worst-case complexity are O(nLogn) and image.png(n2), respectively.

### Quick Sort implementation in C++
Implemented Using vectors in C++ in Codeblocks Ide (MinGW gcc compiler)
#### Header Files Included:
```
 -> iostream
 -> vector
``` 
#### Functions:
```
=> swapp(vector<int>,int,int) 
    ->Swap 2 values of the array(index of elements as parameters)

=> partition
    -> returns the index of correct position of pivot element passed
    
=> quicksort
    ->Recursive function to do the sorting on partitioned vectors
  
=> main
    ->Get the vector from the user, calls the quicksort function on the vector and displays the sorted vector.
