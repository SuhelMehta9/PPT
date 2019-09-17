# Dynamic Programming

---

## What is dynamic programming?
- It is a way of making an algorithm more efficient by storing some of the intermediate results.
- It works well when our algorithm has lots of repetitive computations.
- We can use recurrsion to solve the programming problems but iteration method is mostly used.
- It is based on prncipal of optimality.
- Example:- Fibonacci number series


Note:
- Principal of optimality states that a problem can be solved by taking sequence of decisions to get the optimal solution.
- means we can solve larger problems given the solution to it's smaller sub-problems

---

## Steps for dynamic programming

- Recursion
- Store (memoize)
- Bottom-up 

---
### Recursion
Recursion is the process which comes into existence when a function calls a copy of itself to work on a smaller problem. 

---
### Store or memoize
In our recursive solution if we notice that there are repetitive computations then store them.

"memoize != memorize"

---
### Bottom-up 
Going bottom-up is a way to avoid recursion, saving the memory cost that recursion incurs when it builds up the call stack. Put simply, a bottom-up algorithm "starts from the beginning," while a recursive algorithm often "starts from the end and works backwards."

Note:
- In computing, memoization or memoisation is an optimization technique used primarily to speed up computer programs by storing the results of expensive function calls and returning the cached result when the same inputs occur again.


---
## Let us see an example for Fibonacci series using those three approach

---
## Fibonacci series using Recurrsion
### 1,1,2,3,5...

![](https://lab.gdy.club/~mehta/fibrecursion.png) 

Note:
- Now what dynamic programming says that fib(3) and fib(2) can be stored.


---
![](https://lab.gdy.club/~mehta/memo1.png)
---
![](https://lab.gdy.club/~mehta/memo2.png)
---
![](https://lab.gdy.club/~mehta/memo3.png)
---

![](https://lab.gdy.club/~mehta/bottom-up.png)

---
# [Python Code](https://scraping-suhelmehta.notebooks.azure.com/j/notebooks/Dynamic%20programming.ipynb)

---
# Difference between 
# Greedy method
# And
# Dynamic Programming

---
- In greedy method we have a predefined path to follow and we assume that the path or algorithm we are following is optimal ***but*** in case of dynamic programming every stage we take a decision.

- Greedy algorithm never reconsiders its choices whereas Dynamic programming may consider the previous state.
- Greedy algorithm is less efficient whereas Dynamic programming is more efficient.
- Greedy algorithm have a local choice of the sub-problems whereas Dynamic programming would solve the all sub-problems and then select one that would lead to an optimal solution.

---
- Greedy algorithm work based on choice property whereas Dynamic programming work based on principle of optimality.
- Greedy algorithm follows the top-down strategy whereas Dynamic programming follows the bottom-up strategy.
