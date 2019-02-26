# Merge-K-sorted-LinkedList
C++ code to Merge K-sorted LinkedList 
We have to merge K-sorted linkedlist into single list and return the head of final list
We have used min heap to get a the smallest value node among the first node of each linkedlist
Min heap of size K is used which holds the first smallest node(at that moment) from each K-list;
To delete element from min heap of size K is K(logK) {logK for heipify}
so overall Time complaxity will be O(nK(logK))
Space Complaxity wil be O(K)  {since K size heap is used}
