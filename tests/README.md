Top N Items Function
This function, top_n, retrieves the top N items from a list in descending order.

Usage:

from mypackage import myModule

# Example 1
result = myModule.top_n([8, 3, 2, 7, 4], 3)
print(result)  # Output: [8, 7, 4]

# Example 2
result = myModule.top_n([10, 1, 12, 9, 2], 2)
print(result)  # Output: [12, 10]

# Example 3
result = myModule.top_n([1, 2, 3, 4, 5], 5)
print(result)  # Output: [5, 4, 3, 2, 1]


Parameters
items (list): A list or array-like object containing numerical values.
n (int): The number of top items to return.

Returns
list: The top N items, in descending order.


EXAMPLES :

top_n([8, 3, 2, 7, 4], 3)  # Returns: [8, 7, 4]
top_n([10, 1, 12, 9, 2], 2)  # Returns: [12, 10]
top_n([1, 2, 3, 4, 5], 5)  # Returns: [5, 4, 3, 2, 1]
