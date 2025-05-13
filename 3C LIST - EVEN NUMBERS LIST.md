# Exp.No:3c
## LIST - EVEN NUMBERS LIST

---

### AIM  
To write a Python function that accepts a number **N** and creates a list containing all even numbers up to **N**.



### ALGORITHM

1. Begin the program.  
2. Accept an integer `a` from the user.  
3. Create an empty list `l`.  
4. Use a `for` loop to iterate through numbers from `1` to `a - 1`:  
   - For each number `i`, check if it is even using `i % 2 == 0`.  
   - If it is even, append `i` to the list `l`.  
5. Print the final list `l` containing all the even numbers.  
6. Terminate the program.



### PROGRAM

def get_even_numbers_up_to_n():
    
   N = int(input("Enter a number (N): "))
    
    
   even_numbers = [num for num in range(2, N + 1, 2)]
    
   print("Even numbers up to", N, "are:", even_numbers)

get_even_numbers_up_to_n()

### OUTPUT
![image](https://github.com/user-attachments/assets/389a125e-97ea-4ca5-8da3-9afb6be8609f)

### RESULT
Thus the Python function that accepts a number **N** and creates a list containing all even numbers up to **N** was successfully executed.


