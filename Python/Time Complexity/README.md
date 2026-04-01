# ⏱️Understanding Time Complexity
Time complexity is used to measure how much time an algorithm takes as the input size increases.It helps to compare different approach of the algorithms.It is important to find the efficiency.

## Why Time Complexity is Important ? ⭐
- It helps to choose efficient algorithms
- It improves performance of programs
- It is important for handeling large data
- It is commonly asked in coding interviews

## Types of Time Complexity
| Complexity | Name |
|------------|------|
| O(1)|Constant Time|
|O(log n)|Logarithmic Time|
|O(n)|Linear Time|
|O(n^2)|Quadratic Time|

## Example 1: Linear Time O(n)

```python
for i in range(n):
print(i)
```
This loop runs n times.

Time Complexity : O(n)

## Tips to Analyze Time Complexity
- Ignore constants (O(2n) -> O(n))
- Focus on highest power term
- Nested Loops multiply (O(n*n) = O(n^2))
- Sequential Loops add (O(n + n) = O(n))

## Conclusion

Time complexity helps us understand how efficient an algorithm is.

It is important for writing optimized code and solving problems effectively.





