You are given 3 integers- n,x,y.
The score of a permutation is the sum of elements whose index is divisible by x,minus the sum of elements whose index is divisible by y.

You need to find the maximum score among all permutations of length n.

For example if n=7,x=2,y=3 then the maximum score achieved by the array (permutation) is (6+7+4)-(1+4)=12

A Permutation of length n is an array containing values from 1 to n in any order where no value is repeated more than once in the array


Input Format:
1. The first line contains 3 integers n,x,y

Constraints:
- 1 <=n <= 10^9
- 1 <= x,y <=n

Ouput Format:
- Print the maximum score