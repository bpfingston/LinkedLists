# Big O  

## What I learned?  

1. BigO is used to describe the Worst Case of effeciency of an algorith or function, and evaluates based on 2 things:  
    - Space: the amount of memory resources a function uses to store data and instructions.  
    - Time: the amount of time a funciton needs to complete.  

2. There are 4 things to consider:  
    - Input Size: this refers to number of parameters that an algorithm has to read, as well as the size of each parameter value as well. The higher the number the increased strain on Running time and Memory Space.  
    - Units of Measurement: which refers to measuring time in 3 ways and space in 4.  
        - Time:  
            1. Milliseconds - the time it takes from start of function to the end.  
            2. Operations - the number of lines of code that are executed.
            3. Basic Operations - the operation that is contributing the most to the total runtime.  
        - Space:  
            1. Code for the algorithm - the amount of space needed to store the characters for the instructions specified in your function.   
            2. Input data - just the amount needed to hold.  
            3. Output data - the amount needed.  
            4. Working Space/Stack Space - the amount needed as our functions perform calculations.  
    - Orders of Growth: as overall efficiency increases, as does Orders of Growth, which represents the increase in Running Time or Memory Space.  
        - Types of Complexity (O(1)):
            1. Constant Complexity - doesn't matter the input, it will use the same amount of time and space.  
                - No matter the size of `a` and `b`, the function will always return the sum of those two numbers.  
            2. Logarithmic Complexity(O(lgn)) - a decrease in the rate of complexity growth, as the input value increases.  s
                - Generally sorted data.    
            3. Linear Complexity (O(n))- the value of the inputs will directly determine the amount of Memory(space) used and Running(time) length.   
                - Often used for Loops and recursion.  
            4. Linearithmic Complexity(O(n*lgn)) - when the growth rate of the linear input value is increase by the increase of sorted data.  
                -Genearlly when we are searching through an Array of sorted Arrays.  
            5. Quadratic Complexity(O(n^2)) - when the complextiy growth rate input size, muplitilies by a factor of itself.   
                - Generally nested loops that are iterative or recursive, and perform the action again for each value of n.
                - Think of 2 for() loops.  
            6. Cubic Complexity(O(n^3)) - a step above Quadratic Complexity, can be done by nesting more loops.   
                - Think of 3 for() loops.   
            7. Exponential COmplexity (O(2^n)) - whatever the input size, the amount of times we iterate through the loop.   
                - Fibonacci sequence, where the sum that is displayed increases at a fast pace.(1,1,2,3,5,8,13,21)  
            8. Facotrial Complexity (n!) - where space and time requirements grow extremely fast. Happens when we need to calculate every possible event of a specific scenario.  
                - consider the amount of ways that you could stack a deck of cards, with all 52 cards. its an insane amount.  
    - Best, Average, Worst Case:
        1. Best Case: the quickest scenario, and search for values are easy to find.  
            - Also known as Big Omega.  
        2. Average Case: an assumption of the possible input values and how they might affect efficiency(not an average of best and worst case).   
            - Also known as Big Theta.  
        3. Worst Case: the longest scenario, no sorted inputs, and no search values or last to be searched.  
            - Also known as BigO.(oh no, oh no, oh no no no).  
