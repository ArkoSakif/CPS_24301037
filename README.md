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
I approached this problem by starting to measure the area from the two extreme sticks
I initialized two variables, start and end, I also initialized the max value(max=0) that will klatern return the maximum area possible after the operation has been done
start is intialized with 0, indicating the very start of the array and end is initialized with (array's length-1) indicating the last index of the array
a while loop is ran that will go on until start!=end,the first time the loop runs the area created by the extremes sticks will be stored in max,the area is calculated by multiplying the smaller height of the two sticks with the width difference between them(end-start)
the conditional to store in max is if area>max it will be stored, and since max was initialized at 0 the first time the loop runs the area automaticcally becomes max
after the max is updated, the code will check which of the sticks has smaller height,if the start stick has smaller height start will be incremented else if the end stick has a smaller height , end will decrement
this method is used to check if the a greater area with the taller stick is possible 
eventually by incrementing and decrementing, start and end will become equal and the loop will break
at this point the actual max area has been updated , after the loop ends the max value is returned

