3. Print a list of integers... in reverse!
mandatory
Write a function that prints all integers of a list, in reverse order.

Prototype: def print_reversed_list_integer(my_list=[]):
Format: one integer per line. See example
You are not allowed to import any module
You can assume that the list only contains integers
You are not allowed to cast integers into strings
You have to use str.format() to print integers
guillaume@ubuntu:~/0x03$ cat 3-main.py
#!/usr/bin/python3
print_reversed_list_integer = __import__('3-print_reversed_list_integer').print_reversed_list_integer

my_list = [1, 2, 3, 4, 5]
print_reversed_list_integer(my_list)

guillaume@ubuntu:~/0x03$ ./3-main.py
5
4
3
2
1
guillaume@ubuntu:~/0x03$ 
Repo:

GitHub repository: alx-higher_level_programming
Directory: 0x03-python-data_structures
File: 3-print_reversed_list_integer.py
   
4. Replace in a copy
mandatory
Write a function that replaces an element in a list at a specific position without modifying the original list (like in C).

Prototype: def new_in_list(my_list, idx, element):
If idx is negative, the function should return a copy of the original list
If idx is out of range (> of number of element in my_list), the function should return a copy of the original list
You are not allowed to import any module
You are not allowed to use try/except
guillaume@ubuntu:~/0x03$ cat 4-main.py
