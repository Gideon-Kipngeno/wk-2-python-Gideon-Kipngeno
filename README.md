# Data-Structures

**Project Overview**

This project demonstrates the use of Python lists and common operations such as adding, inserting, extending, removing, sorting, and finding elements. The goal is to help beginners understand how lists work and how to manipulate them effectively.

**Features**

1. Create an empty list
2. Append elements to a list

3. Insert an element at a specific position

4. Extend the list with another list

5. Remove the last element

6. Sort the list in ascending order

7. Find the index of a specific value

**Setup**

Make sure you have Python 3 installed on your machine.

Clone this repository:

git clone https://github.com/Gideon-Kipngeno/wk-2-python-Gideon-Kipngeno.git


Navigate to the project folder:

    cd wk-2-python-Gideon-Kipngeno
    
Open the list_operations.py file in your preferred Python IDE or editor.

**How to Run**

Run the Python script using:

python Data_structures.py

**Project Instructions**

Create an empty list called my_list.
    my_list = []
    print("1. Empty list:", my_list)

Append the elements 10, 20, 30, 40 to the list.
# 2. Append the following elements to my_list: 10, 20, 30, 40
    my_list.append(10)
    my_list.append(20)
    my_list.append(30)
    my_list.append(40)
    print("2. After appending:", my_list)


Insert the value 15 at the second position.
# 3. Insert the value 15 at the second position in the list
    my_list.insert(1, 15)  # Index 1 is the second position (0-based indexing)
    print("3. After inserting 15 at position 2:", my_list)

Extend my_list with [50, 60, 70].
# 4. Extend my_list with another list: [50, 60, 70]
    my_list.extend([50, 60, 70])
    print("4. After extending:", my_list)

Remove the last element from the list.
# 5. Remove the last element from my_list
    my_list.pop()
    print("5. After removing last element:", my_list)

Sort the list in ascending order.
# 6. Sort my_list in ascending order
    my_list.sort()
    print("6. After sorting:", my_list)

Find and display the index of the value 30.
# 7. Find and print the index of the value 30 in my_list
    index_of_30 = my_list.index(30)
    print("7. Index of 30:", index_of_30)

**Expected Output**
# Final list
    print("Final my_list:", my_list)

After running the script, the program will print the state of the list at each step, showing how the list changes after every operation, and finally display the index of 30.

**Learning Outcomes**

Understand Python list operations (append, insert, extend, pop, sort, index)

Learn how to manipulate and access elements in lists

Build a solid foundation for more advanced data structures