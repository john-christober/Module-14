# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```
Name : John christober
Reg No : 212222060098
from collections import deque

# Initial deque with input characters
d = deque(['p', 'y', 't'])

# Appending elements at the rear end
d.append('h')
d.append('o')
d.append('n')

# Printing the result
print("The deque after appending at right is :")
print(d)

```

### OUTPUT
<img width="963" height="211" alt="image" src="https://github.com/user-attachments/assets/d2c55221-3bb1-44bb-b639-8701120d978a" />

### RESULT
Thus the Python program to insert elements at REAR END of deque using a collection built-in function is implemented and executed successfully.
