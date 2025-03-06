Assignments explanation
Assignment 01
1a-
the initialization of i,j,k has a complexity of O(1)
the outer loop starts from i=n/2 with i incrementing by 1 each time and ends when i reaches n,therefore the loop runs n/2 time hence it has an time complexity of O(n)
in the inner loop j is initialized at 2 and it increments by j*2 each time therefore to reah n the loop runs for some k sssuh that 2^k=n,rearranging to make k the subject we get that the time complexity for the inner loop is 0(logn)
therefore the time complexity for the whole operation:
O(1)*O(n)*O(logn)=O(nlogn)
1b-
the initialization of x has a time complexity of 0(1)
