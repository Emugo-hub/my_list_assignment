# Python List Operations Program

## 📌 Description
This Python program demonstrates basic list operations such as:
- Creating an empty list
- Appending elements
- Inserting at a specific position
- Extending the list with another list
- Removing the last element
- Sorting in ascending order
- Finding the index of a specific value

It’s a beginner-friendly example for learning Python list methods.

---

## 🖥️ Code Example
```python
# Step 1: Create an empty list
my_list = []

# Step 2: Append elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Step 4: Extend with [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element
my_list.pop()

# Step 6: Sort in ascending order
my_list.sort()

# Step 7: Find the index of 30
index_of_30 = my_list.index(30)

# Print the results
print("Final list:", my_list)
print("Index of 30:", index_of_30)

📊 Example Output

Final list: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3

🚀 How to Run

    Ensure Python is installed on your machine.

    Save the code in a file, e.g., list_operations.py.

    Open a terminal and run:

    python list_operations.py

🛠️ Technologies Used

    Python 3

📚 Learning Points

    Using append() to add elements

    Using insert() to add at a specific index

    Using extend() to join lists

    Using pop() to remove elements

    Using sort() to arrange in ascending order

    Using index() to find element positions

✍️ Author

Eric Gitonga Mugo


