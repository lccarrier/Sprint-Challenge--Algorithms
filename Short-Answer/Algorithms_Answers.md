#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)
‘a’ grows at a constant rate of n^2
The loop finishes when ‘a’ is at n^3
It takes ‘n’ iterations for the loop to finish since n^3/n^2 = n


b) O(n log (n))
The outer for-loop takes “n” operations to terminate. 
The inner while-loop takes log(n) operations to terminate (because the loop finish when “j” is equal to “n”, and “j” grows exponentially, doubling each time.


c) O(n)
bunnyEars is called recursively until “bunnies” reaches 0, with “bunnies” reducing by 1 every time. So it takes “n” iterations for the function to terminate.

## Exercise II
Using a binary search, the overall goal is to search through n floors to find floor f. Start at the middle floor. Drop an egg from this floor. If the egg doesn't break, eliminate current the floor and all the ones below. If the egg breaks, eliminate all the floors above. Continue until only two are left; where f would be the higher of the two.


