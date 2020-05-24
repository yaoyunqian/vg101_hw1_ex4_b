# vg101_hw1_ex4_b
A brief introduction to binary search.

**Binary search**, also known as **half-interval search**, is an convenient approach to search for a certain number in a sorted group of numbers.

The logic behind binary search
------
When given n sorted numbers, split the group into halves:
* if n is even, first check whether the n/2th number is the wanted one.
* if n is odd, first check whether the (n+1)/2th number is the wanted one.

Then repeat the process above, with n being reduced to:
* half of its original value if n is even.
* half of the original (n+1) if n is odd.
Repeat until the expected number is found.

Ways to carry out a binary search
------
* Loop (while *not found*)
* Recursion
