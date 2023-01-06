# Shortest-Prime-Path
Shortest Prime Path
You are given two four digit prime numbers Num1 and Num2. Find the distance of the shortest path from Num1 to Num2 that can be attained by altering only one single digit at a time. Every number obtained after changing a digit should be a four digit prime number with no leading zeros.
### Example 1:
Input:<br>
Num1 = 1033<br>
Num2 = 8179<br>
Output: 6<br>
Explanation:<br>
1033 -> 1733 -> 3733 -> 3739 -> 3779
                 -> 8779 -> 8179.<br>
There are only 6 steps required to reach
Num2 from Num1, and all the intermediate
numbers are 4 digit prime numbers.

### Your Task:  
You don't need to read input or print anything. Your task is to
Complete the constructor of the class Solution to precompute a list of prime numbers.  
Complete function shortestPath() which takes two integers Num1 and Num2 as input parameters and returns the distance of the shortest path from Num1 to Num2. If it is unreachable then return -1.
