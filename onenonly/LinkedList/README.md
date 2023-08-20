# Linked List Libraries - singlyLinkedList and doublyLinkedList
The Linked List Libraries (singlyLinkedList and doublyLinkedList) are Python classes that provide implementations of singly linked lists and doubly linked lists, respectively. Linked lists are fundamental data structures used to store and manage collections of elements efficiently. These libraries aim to simplify the creation, manipulation, and analysis of linked lists.

# Installation
```bash
pip install onenonly
```

# Usage
singlyLinkedList Usage
The singlyLinkedList class provides a singly linked list implementation. Here's how you can use it:

```python
# Import the singlyLinkedList class
from onenonly.LinkedList import singlyLinkedList

# Create a singly linked list
sll = singlyLinkedList()

# Append elements to the list
sll.append(5)
sll.append(10)
sll.append(15)

# Display the list
sll.display()  # Output: 5 > 10 > 15 > None

# Get the length of the list
sll.length()   # Output: 3

# Check if an element is present in the list
sll.isPresent(10)  # Output: True

# Get the index of an element in the list
sll.indexOf(15)   # Output: 2

# Get the value at a specific index
sll.valueAt(1)    # Output: 10

# Remove an element from the list
sll.remove(10)
sll.display()  # Output: 5 > 15 > None
```

# doublyLinkedList Usage
The doublyLinkedList class provides a doubly linked list implementation. Here's how you can use it:

```python
# Import the doublyLinkedList class
from onenonly.LinkedList import doublyLinkedList

# Create a doubly linked list
dll = doublyLinkedList()

# Append elements to the list
dll.append(5)
dll.append(10)
dll.append(15)

# Display the list
dll.display()  # Output: 5 < > 10 < > 15 < > None

# Get the length of the list
dll.length()   # Output: 3

# Check if an element is present in the list
dll.isPresent(10)  # Output: True

# Get the index of an element in the list
dll.indexOf(15)   # Output: True

# Get the value at a specific index
dll.valueAt(1)    # Output: 10

# Remove an element from the list
dll.remove(10)
dll.display()  # Output: 5 < > 15 < > None
```