# PLP_Python_assignment_3
# Discount Calculator

This program allows users to calculate the final price of an item after applying a discount. If the discount is 20% or higher, the program will apply the discount and return the reduced price. If the discount is below 20%, no discount will be applied, and the original price will be returned.

## Function: `calculate_discount(price, discount_percent)`

### Parameters:
- `price` (float): The original price of the item.
- `discount_percent` (float): The discount percentage to apply.

### Returns:
- `float`: The final price after applying the discount, or the original price if no discount is applied.

### Discount Rule:
- If the discount percentage is **20% or higher**, the discount is applied.
- If the discount percentage is **less than 20%**, the original price remains unchanged.

### Example:
```python
calculate_discount(100.0, 25)  # Returns 75.0
calculate_discount(50.0, 15)   # Returns 50.0
