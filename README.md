# Python List Manipulation Example

This repository demonstrates basic list operations in Python, including appending, inserting, extending, removing, sorting, and indexing.

## Code Overview

The script performs the following operations on a Python list:

1. **Create an empty list**  
   ```python
   my_list = []
   ```

2. **Append elements to the list**  
   Adds `10`, `20`, `30`, `40` to `my_list`.
   ```python
   my_list.append(10)
   my_list.append(20)
   my_list.append(30)
   my_list.append(40)
   print("After appending 10, 20, 30, 40:", my_list)
   ```

3. **Insert an element at a specific position**  
   Inserts `15` at the second position (index `1`).
   ```python
   my_list.insert(1, 15)
   print("After inserting 15 at position 2:", my_list)
   ```

4. **Extend the list with another list**  
   Adds `50`, `60`, and `70` to the end of `my_list`.
   ```python
   my_list.extend([50, 60, 70])
   print("After extending with [50, 60, 70]:", my_list)
   ```

5. **Remove the last element**  
   Removes the last item from the list.
   ```python
   my_list.pop()
   print("After removing the last element:", my_list)
   ```

6. **Sort the list in ascending order**  
   Sorts all elements from least to greatest.
   ```python
   my_list.sort()
   print("After sorting in ascending order:", my_list)
   ```

7. **Find the index of a specific value**  
   Finds the index of value `30` in the list.
   ```python
   index_of_30 = my_list.index(30)
   print("Index of value 30:", index_of_30)
   ```

## How to Run

1. Save the code from above into a Python file, for example `list_example.py`.
2. Run the file:
   ```
   python list_example.py
   ```

You will see the output after each operation, illustrating how the list changes.

## Output Example

```
After appending 10, 20, 30, 40: [10, 20, 30, 40]
After inserting 15 at position 2: [10, 15, 20, 30, 40]
After extending with [50, 60, 70]: [10, 15, 20, 30, 40, 50, 60, 70]
After removing the last element: [10, 15, 20, 30, 40, 50, 60]
After sorting in ascending order: [10, 15, 20, 30, 40, 50, 60]
Index of value 30: 3
```

## License

This example is provided for educational purposes.
