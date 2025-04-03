# CMPS 2200 Recitation 06
## Answers

**Name:**Camden Yale
**Name:**Emily Aymond


Place all written answers from `recitation-07.md` here for easier grading.



- **2)** W(n) = W(n - 1) + W(n - 2) + O(1)
  
-  W(n) when n = 1: W(n) = O(2^n - 1) + O(2^n - 2) + O(1) = O(2^n)

- **3)** S(n - 1) + 1 = O(n)

- **4)** Higher Fibonacci numbers are calcualted many more times than smaller numbers. This is because of overlapping subproblems. 

- **6)** The work and span for fib_top_down is O(n).

  
- Work is proportional to number of Fibonacci numbers computed, which is O(n).
- Span is proportional because they can be computed in parallel. 

- **8)** The work and span of fib_bottom_up are both O(n).

- This is because the maximum number of times that will be read for Fi any value i is 1. 
