[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/T6sJM4w6)

# Week 5 — Midnight Mail Train

## Summary
This assignment implements a doubly linked list to manage train cars, including adding, removing, and traversing cars. It also includes string validation and recursive functions for counting labels and cleaning messages. The goal is to practice linked lists, recursion, and basic string processing.

## Approach
- Problem 1:
  Implemented a doubly linked list with head and tail pointers. Used pointer updates to append and remove nodes efficiently.
  
- Problem 2:
  Validated ticket codes by checking prefix "MM-" and ensuring the remaining part contains exactly 4 digits.
  
- Problem 3:
  Used recursion to count occurrences of a target label by reducing the list one element at a time.
  
- Problem 4:
  Used recursion to remove spaces from a string by processing one character at a time.

## Complexity
- append_car:
  Time: O(1), Space: O(1)
  Reason: Direct insertion using tail pointer.

- detach_last_car:
  Time: O(1), Space: O(1)
  Reason: Direct removal using tail pointer.

- to_reverse_list:
  Time: O(n), Space: O(n)
  Reason: Traverses all nodes and stores results in a list.

- is_valid_ticket_code:
  Time: O(1), Space: O(1)
  Reason: Fixed-length string check.

- count_priority_labels (recursive):
  Time: O(n), Space: O(n)
  Reason: Visits each element once, recursion uses call stack.

- clean_radio_message (recursive):
  Time: O(n), Space: O(n)
  Reason: Processes each character and builds a new string recursively.

## Edge-case checklist
- [x] empty train
- [x] one train car
- [x] invalid ticket code
- [x] empty label list
- [x] empty message
- [x] one-character or all-space message

## Assistance & Sources
- AI used? Y
- What it helped with:
  Helped verify correctness of linked list operations, recursion logic, and formatting of the README.
- Other sources used:
  Course notes and lecture materials