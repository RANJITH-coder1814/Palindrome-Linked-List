# Palindrome-Linked-List
A C++ solution for LeetCode Problem 234: Palindrome Linked List. The approach uses the fast and slow pointer technique to find the middle of the linked list, reverses the second half in-place, and compares both halves to determine whether the list forms a palindrome.
Problem Statement

Given the head of a singly linked list, return true if it is a palindrome or false otherwise.

Example 1
Input: head = [1,2,2,1]
Output: true
Example 2
Input: head = [1,2]
Output: false
Approach
Step 1: Find the Middle

Use two pointers:

slow moves one step at a time.
fast moves two steps at a time.

When fast reaches the end, slow will be at the middle.

Step 2: Reverse the Second Half

Reverse the linked list starting from the middle node.

Step 3: Compare Both Halves

Compare values from:

Beginning of the list.
Beginning of the reversed second half.

If all corresponding nodes match, the list is a palindrome.
