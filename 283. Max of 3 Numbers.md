### Description
https://www.lintcode.com/problem/max-of-3-numbers/
Given 3 integers, return the max of them.

### Example
Example 1:
	Input:  num1 = 1, num2 = 9, num3 = 0
	Output: 9
	
	Explanation: 
	return the Max of them.

Example 2:
	Input:  num1 = 1, num2 = 2, num3 = 3
	Output: 3
	
	Explanation: 
	return the Max of them.

### Code
```
class Solution:
    # @param {int} a an integer
    # @param {int} b an integer
    # @param {int} c an integer
    # @return {int} an integer
    def maxOfThreeNumbers(self, a, b, c):
        # Write your code here
        return max(a, b, c)
```
