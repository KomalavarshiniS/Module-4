# EX-16-Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class umbrella:

    def rain(radius):
        return (math.pi*radius*radius)
radius=int(input())
print("Area of circle:",end=" ")
print(round(umbrella.rain(radius),2))
```
## Output
![image](https://github.com/user-attachments/assets/60a66d81-d755-44ba-bb34-24a983be31c8)

## Result
Thus the program that calculates the **area of a circle** based on the radius provided by the user has been executed successfully. 
## EX-17-Dictionary Operations in Python:Size of dictionary.

## 🎯 Aim
Write a  python program to print the size of dictionary using getsizeof() from sys module
## 🧠 Algorithm
1.Import the getsizeof function from the sys module.
2.Define a dictionary my_dict with some key-value pairs.
3.Use the getsizeof() function to get the memory size of the dictionary object.
4.Print the size of the dictionary in bytes.
## 🧾 Program
```
dic1 = {"A": 1, "B": 2, "C": 3} 
import sys
print("Size of dic1: {}bytes".format(sys.getsizeof(dic1)))
dic2 = {"Geek1": "Raju", "Geek2": "Nikhil", "Geek3": "Deepanshu"}
print("Size of dic2: {}bytes".format(sys.getsizeof(dic2)))
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}
print("Size of dic3: {}bytes".format(sys.getsizeof(dic3)))
```
## Output
![image](https://github.com/user-attachments/assets/d9ae3476-7a5e-44b1-b924-863a5f02760e)

## Result
Thus the program to print the size of dictionary using getsizeof() from sys module has been successfully executed.
# EX-18-Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
a={2:56,1:2,5:12,4:24,6:18,3:323}
b=sorted(a.items(),key=lambda item:item[1])
print("Keys and Values sorted in alphabetical order by the value")
print(b)
```
## Output
![image](https://github.com/user-attachments/assets/8f684405-5825-434c-bdd4-cd778a4c5d99)

## Result
Thus the  Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order has been successfully executed.
# EX-19-Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
try:
        a = []
        n = int(input())
        for i in range(n):
            num=int(input())
            a.append(num)
        print(a)
        print(a[6])
except IndexError:
    print("6 is not accepted")
```
## Output
![image](https://github.com/user-attachments/assets/c05da281-7a42-471b-856a-ac42ad307011)

## Result
Thus the program that handles an **IndexError** when trying to access an element beyond the available range of a list has been successfully executed.
# EX-20-File Handling in Python: A file and count the number of words in it.

## 🎯 Aim
Write a Python program to read a file and count the number of words in it.

## 🧠 Algorithm
1.Open the file story.txt in read mode.
2.Read the entire content of the file.
3.Use the split() method to split the text into individual words.
4.Use the len() function to count the number of words.
5.Print the total word count.
## 🧾 Program
```
def create_file(file_path,file_content):
    with open(file_path,'w')as file:
        file.write(file_content)
def count_words_in_file(file_path) :
    with open(file_path,'r')as file:
        content=file.read()
        words=content.split()
        return len(words)
```

## Output
![image](https://github.com/user-attachments/assets/8151767f-1246-4f42-9253-986b47b7cd8d)

## Result
Thus the program to read a file and count the number of words in it has been successfully executed.
