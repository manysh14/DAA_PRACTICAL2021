# DAA_PRACTICAL2021
In Red_black_tree program, if error occurs,then change language standard (-std) to ISO C++11 in the compiler settings.


complexity in Red-Black Tree -
inserting a node - O(log n)
deleting a node - O(log n)
searching a node - O(log n)

Time complexity    bubble    selection   insertion   merge   
best                O(n)      O(n^2)      O(n)        O(nlogn)
average             O(n^2)    O(n^2)      O(n^2)      O(nlogn)
worst               O(n^2)    O(n^2)      O(n^2)      O(nlogn)


quick sort is a divide and conquer approach with  T(n) = T(k) + T(n-k-1) + cn
worst case -  T(n) = T(0) + T(n-1) + cn = O(n^2)
best case -   T(n) = 2T(n/2) + cn = O(nlogn)
average case - T(n) = 2T(n/2) + cn = O(nlogn)
