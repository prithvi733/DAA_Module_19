# EX 1D Linear search
## DATE:
## AIM:
To write a python program for a search function with parameter list name and the value to be searched using string values.



## Algorithm
```
1.Define a function search(List, n)
  • For each element in List:
    – If the current element is equal to n, return True
  • If no match is found after the loop, return False
2.Initialize an empty list List
3.Read an integer x from the user (number of elements in the list)
4.Repeat x times:
  • Read a string from the user and append it to List
5.Read the string n to be searched from the user
6.Call the search(List, n) function
  • If it returns True, print "Found"
  • Else, print "Not Found" 
```
## Program:
```

Program to implement a search function with parameter list name and the value to be searched using string values.
Developed by: V.PRITHVIRAJ
Register Number: 212222100038 

def search(List,n):
    for i in range(len(List)):
        if(List[i]==n):
            return True
    return False

List=[]
x=int(input())
for i in range(x):
    List.append(input())

n=input()

if search(List,n):
    print("Found")
else:
    print("Not Found")
```

## Output:

![image](https://github.com/user-attachments/assets/50b4ce1a-e7a9-41be-9da7-a390bc166393)


## Result:
The program was executed successfully, and it correctly checks if the input element is present in the list, printing "Found" if the element exists or "Not Found" if it does not.
