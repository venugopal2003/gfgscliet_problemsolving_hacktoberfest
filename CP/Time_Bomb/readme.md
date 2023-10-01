The bomb has a timer that is initially set to bEvery second, the timer will decrease by 1.
When the timer reaches 0, the bomb will explode! To give the residents of Snowdin enough time to evacuate, you will need to delay the bomb from exploding for as long as possible.

You have n tools. Each tool can only be used at most once. If you use the i-th tool, the timer will increase by xi
However, if the timer is changed to an integer larger than a, the timer will be set to adue to a bug.

More specifically, the following events will happen every second in the following order:

1. You will choose some (possibly none) of your tools that have not been used before. If you choose the i-th tool, 
    and the bomb's timer is currently set to c, the timer will be changed to min(c+xi,a). 
2. The timer decreases by 1
3. If the timer reaches 0, the bomb explodes.

Print the maximum time in seconds until the bomb explodes if the tools are used optimally.


Input Format:
1. The first line consists of a,b,n.
2. The second line consists of array of n integers.

Constraints:
- 1 ≤ a,b ≤ 10^9
- 1 ≤ n ≤ 100

Output Format:
Print the maximum time in seconds until the bomb explodes if the tools are used optimally.
