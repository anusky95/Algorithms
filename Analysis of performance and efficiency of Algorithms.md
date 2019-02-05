## Time Complexity

#### Big O analysis
- Describes an upper bound on the time.
- Less than or equal to relationship.
- If Bob is X years old, we can assume that X<=130, (Could also be X<=1000, X<=100000)
- Printing all numbers in the array would take O(N) time. (Might as well take O(N^2) or O(N^3) - if you decide to be lazy! )


#### Big Omega
* Describes the lower bound for a program or code.
* Printing the values in array can take Omega(N) or (can also do it in Omega(Log N) and Omega(1) - if you want to challenge yourself!) 

#### Big theta
* An algorithm which is both in O(n) and Omega(n) is said to be in theta(N)


**  Using Quick sort to sort the arrays

Selecting a pivot is the key to success of quicksort
Choosing the last item or first item would be fatal since if it is sorted by any chance the performance would be worse
Divide and conquer algorithm
Very efficient for large datasets
Worst case is O(N2)
Average case is O(N log N)
Selection of pivot: Median of first element, middle element and the last element
2 3 1 8 4 9 6 3 7 5
Ideal pivot above (median(2,4,5) -> 4


Best case : All elements are equal O(N)
Worst Case: Pivot is chosen the first element and array is sorted in reverse order O(N^2)
Expected case: O(N Log N)'

## Space Complexity

O(N) - Space for one array of size N
O(N^2) - Space for array of size N X N 



