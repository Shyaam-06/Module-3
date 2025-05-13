# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.



### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.



### PROGRAM

N = int(input("Enter a number (N): "))


multiples_of_five = tuple(range(5, N + 1, 5))


print("Multiples of 5 up to", N, "are:", multiples_of_five)


### OUTPUT
![image](https://github.com/user-attachments/assets/ce0e4c5a-5115-4540-b6fe-75632ec37506)



### RESULT
Thus the Python program to create a tuple containing all multiples of 5 up to a given number **N** was successfully executed.

