# Number Statistics (Task 5)

Python program that processes a collection of numbers to separate even/odd values and identify the dataset's boundaries.

## 📁 Deliverables
* **`number_statistics.py`**: Python script containing the logic.
* **Separated Lists**: Isolated sets for even and odd numbers.
* **Min/Max Values**: The largest and smallest numbers.

## 💻 Code Structure
```python
numbers = [23, 45, 12, 56, 89, 2, 74, 91, 38, 65]
even_numbers = [num for num in numbers if num % 2 == 0]
odd_numbers = [num for num in numbers if num % 2 != 0]

print(f"Evens: {even_numbers}")
print(f"Odds: {odd_numbers}")
print(f"Max: {max(numbers)} | Min: {min(numbers)}")
```


```bash

```