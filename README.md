# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: CHAITANYA P S
RegisterNumber: 212222230024
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: CHAITANYA P S
RegisterNumber: 212222230024
'''
def max_marks(marks):
    marks=max(marks)
    return marks
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: CHAITANYA P S
RegisterNumber:212222230024 
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot 2023-06-15 122251](https://github.com/chaitanya18c/FindMaximum/assets/119392724/5b99b8d7-901a-4246-be00-a4b71339f2a6)
![Screenshot 2023-06-15 122302](https://github.com/chaitanya18c/FindMaximum/assets/119392724/f35c438e-51d9-4870-a401-7942b27d76e5)
![Screenshot 2023-06-15 122312](https://github.com/chaitanya18c/FindMaximum/assets/119392724/a707ab91-2ed3-4e8e-bd17-01112b49fece)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
