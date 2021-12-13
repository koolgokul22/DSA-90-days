# DSA-90-days
A repository to track my DSA progress 

https://whimsical.com/dsa-in-90-days-EmPkf5utoFGRMnRqJjM6YV
 

Space and Time Complexity ( Day 1-2 )
  
    1.Analysis of  Algorithms
    
   
    2.Asymptotic Analysis
    
      - Measures the order of growth.   
      
      - Consider only those terms that have highest order growth and ignore the remaining terms. 
      
      
    3.Order of Growth
    
      - How fast the program execution time f(n) increases wrt to the input size 'n' , where f(n) is program execution time.   
      
      - c < log log(n) < log(n) < n^(1/3) < n^(1/2) < n < n log(n) < n^2 < n^3 < 2^n < e^n < n^n
      
      
     4.Best, Average, Worst Case
      
      - We always consider the worst case scenario.
      
      
     5.Asymptotic Notations
     
      - Represents the order of growth in mathematical form.
      
      - Big O => Exact or upper bound
      
      
      - Theta => Exact bound
      
      - Omega => Exact or lower bound
      
      - We are interested in exact or upper bound notation.
      
      
     6.Analysis of Recursion
     
      - Recurrence Relations
      
     7.Space Complexity
      
      - Space Complexity -> Order of growth of space or memory (RAM size) with respect to the input size 'n'.
      
      - Auxiliary Space Complexity -> Order of growth of  EXTRA memory space or (RAM memory) with respect to the input size 'n'.
     
Recursion and Backtracking ( Day 3-10 )

    1.Recursion 
  
    - A function calling itself directly or indirectly is called as Recursion.

    - Direct recursion -> A function calls itself directly inside the same function. 
  
     int fun(int n){
      ----
      ----
      return fun(n-1);
     }
   
    - Indirect recursion -> A function indirectly calls itself through another function.

     int fun1(){
      ---
      ---
      fun2()
      ---
      }
    
     int fun2(){
      ---
      ---
      fun1()
      ---
      }
      
