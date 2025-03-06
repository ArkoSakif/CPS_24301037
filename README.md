Assignments explanation


Assignment 01
1a-
the initialization of i,j,k has a complexity of O(1)
the outer loop starts from i=n/2 with i incrementing by 1 each time and ends when i reaches n,therefore the loop runs n/2 time hence it has an time complexity of O(n)
in the inner loop j is initialized at 2 and it increments by j*2 each time therefore to reah n the loop runs for some k sssuh that 2^k=n,rearranging to make k the subject we get that the time complexity for the inner loop is 0(logn)
therefore the time complexity for the whole operation:
O(1)*O(n)*O(logn)=O(nlogn)(Ans)
1b-
the initialization of x has a time complexity of 0(1)
after x has been passed to the function, if it is not 0 or 1,i and result has been initialized whose combined time complexity is O(1)
after that a loop starts which runs until result<x, inside the loop result is i*i i.e. the loop will run until i^2<x (i is incremented by 1 each time) 
the loop breaks when i^2 is greater than x therefore it means that the loop runs as long as i=<√ x, so the maximum value of i here can be i=√ x therefore the time complexity for this loop will be O(√ x)
Now, the time complexity for the whole operation = O(1)*O(1)*O(√ x)=O(√ x)(Ans)

2a-
We approah this problem by 
