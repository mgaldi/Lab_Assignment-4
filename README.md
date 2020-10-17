# Lab_Assignment-4
Programmer: Marco Galdi
Class: CS245
Date: 10/16/2020

## Description
The class LinkedList defines a data structure consisting of two attributes: its number of elements, defined by the variable size, and a pointer to its first node, contained in the variable head.
Each node representaion is contained in a Node data structure, which contains a reference to an object of generic type in the item variable and a pointer to the subsequent node.

The next variable in the last node of the struture is always null.

The main methods exposed by the class are the following:
- get(int position): returns the element in the specifiec position.
- add(E item): appends the specified item at the end of the list.
- add(E item, int position): inserts the specified item in the specified position of the list; if an element is already present at the specified position, that and all the subsequent items slide one position to the right to accomodate the new item.
- remove(int position): removes the item in the specified position; if other items follow the item to remove, these are moved one position to the left.
- reverse(): reverses the list on itself.

# Complexity
All the methods have a complexity of O(n), since for every operation in the worst case scenario the entire list must be scrolled from head to tail.

The method reverse has a O(n) fixed complexity of for every execution.
