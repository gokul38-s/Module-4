## Classes and Objects in Python: Calculate the Area of a Circle
## Name : Gokul S
## Reg No : 212225060070
🎯 Aim

To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

🧠 Algorithm

Get user input: Take the radius of the circle as input from the user.
Define the class: Create a class named cse.
Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula:
Area = pi *r^2
Execute the program: Create an object of the class and call the method with the radius value.

🧾 Program

```
import math
class Cse:
    def mech(self,radius):
        area=math.pi*radius*radius
        print(f"Area of circle: {area:.2f}")
r=int(input())
obj=Cse()
obj.mech(r)
```

Output:
![Screenshot 2025-04-28 225525](https://github.com/user-attachments/assets/732d2ade-138c-4452-af08-c761fa1b92fd)


Result:

Thus to write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation is done successfully.

## Dictionary Operations in Python: Merging Two Dictionaries

🎯 Aim

To write a Python program that merges two dictionaries and combines their key-value pairs.

🧠 Algorithm

Define two dictionaries dict1 and dict2 with some key-value pairs.
Define a function merge() that merges the two dictionaries using the ** unpacking operator.
The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
Call the merge() function and print the merged dictionary.

🧾 Program

```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```

Output:

![Screenshot (145)](https://github.com/user-attachments/assets/e8333efb-3f5c-488e-bca7-cb30b9252da2)

Result:

Thus to write a Python program that merges two dictionaries and combines their key-value pairs is done successfully.


## 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values
This Python program demonstrates how to sort a dictionary:

Alphabetically by keys
Alphabetically by values

🎯 Aim

To write a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order

🧠 Algorithm

Start the program.
Define a dictionary with key-value pairs.
Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
End the program.

🧪Program

```
d={2: 56, 1: 2, 4: 24, 6: 18, 3: 323, 5: 12}
sorted_items=sorted(d.items(),key=lambda x:x[1])
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
```

Sample Output:

![Screenshot (145)](https://github.com/user-attachments/assets/e8333efb-3f5c-488e-bca7-cb30b9252da2)

Result:

Thus the Python program demonstrates how to sort a dictionary:
Alphabetically by keys
Alphabetically by values is done successfully.


## Exception Handling in Python: Avoiding Index Errors

🎯 Aim

To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

🧠 Algorithm

Define a list list1 with some integer elements.
Use a try-except block:
In the try block, attempt to access an index that is out of range (e.g., list1[5]).
In the except block, catch the error and print a custom message "You're out of list range".
Print the result based on whether the index access succeeds or fails.

🧾 Program

```
try:
    n=int(input())
    a=[]
    for i in range(n):
        num=int(input())
        a.append(num)
    index=int(input())    
    print(a)
    print(a[index])
except IndexError:
    print(f"{index} is not accepted")
```

Output:

<img width="712" height="377" alt="image" src="https://github.com/user-attachments/assets/d96e6192-b83f-4ee9-a5a3-9a9e4521401b" />

Result:

Thus to write a Python program that handles an IndexError when trying to access an element beyond the available range of a list is done successfully.


## File Handling in Python: Count Lines Not Starting with 'T'

🎯 Aim

To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.

🧠 Algorithm

Open the file story.txt in read mode.
Initialize a counter count to zero.
Iterate through each line of the file:
Check if the first character of the line is not 'T'.
If the line does not start with 'T', increment the count by 1.
After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.

🧾 Program

```
count = 0

try:
    with open('story.txt', 'r') as file:
        for line in file:
            if not line.strip().startswith('T'):
                count += 1
    print(count)
except FileNotFoundError:
    print("The file 'story.txt' was not found.")
```

Output:

<img width="682" height="173" alt="image" src="https://github.com/user-attachments/assets/ce807ccf-933e-4962-ac63-9a912474f760" />


Result:

Thus to write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T' is done successfully.




