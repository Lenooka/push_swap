# Push_swap
Push_swap is an algorithmic sorting project from the 42 School curriculum focused on sorting data 
using a limited set of stack operations. It emphasizes optimization, implementing efficient strategies
like the longest increasing subsequence (LIS) to minimize moves and improve performance.

# Features
* Sorting using two stacks (a and b)
* Limited set of stack operations (sa, pb, ra, etc.)
* Optimized algorithm based on the Longest Increasing Subsequence (LIS)
* Efficient handling of small and large datasets
* Input validation and error handling

# Algorithm

## The core strategy is based on the Longest Increasing Subsequence (LIS):

* Identify the LIS in the input stack
* Keep LIS elements in stack a
* Push non-LIS elements to stack b
* Reinsert elements from b into a in optimal positions
* Perform final rotations to fully sort the stack

# Technologies
* Language: C
* Compiler: cc / gcc
* Build system: Makefile

# Learning Goals
* Understanding stack-based algorithms
* Optimizing for operation count
* Working with time/space complexity trade-offs
* Implementing and applying LIS in practice
