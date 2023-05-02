# CMPS 2200 Assignment 5
## Answers

**Name:**________Shira__Rozenthal________

Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**

The greedy algorithm would repeatedly select the coin of highest denomination that can fit, doing so over and over again until reaching the given dollar amount. Given that the set of denomination is singular (base 2) and we have a fixed dollar amount, the greedy algorithm is optimal here. 



- **1b.**

W(n) = O(log(n)) and S(n) = O(log(n)) because the algorithm applies log_2(n) over and over again until n=0, which is a serial process.  







- **2a.**

Suppose there exist 1, 5, and 6 denominations and you need 10. The greedy algorithm would take the highest denominations and return 5 coins {6, 1, 1, 1, 1}. The non-greedy algorithm, on the other hand, would only return 2 coins {5, 5}.




- **2b.**

With dynamic programming, we want to implement a bottom-up approach by building a table of denominations and their powers. The work is equal to all the nodes of DAG, or W(n) = O(nk) where n is the length of the set of denominations and k is the highest powers. The span is the longest path in DAG, which is just S(n) = O(n). 
