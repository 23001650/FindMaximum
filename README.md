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
Developed by:SUNIL KUMAR T 
RegisterNumber: 23001650
'''
def max_marks(marks):
    marks.sort()
    num2=marks[-1]
    return num2




```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: SUNIL KUMAR T
RegisterNumber: 23001650
'''
def max_marks(marks):
    mark_high=max(marks)
    return mark_high


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by:SUNIL KUMAR T 
RegisterNumber:23001650 
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output](/Screenshot%202023-07-25%20144402.png)
![output](/Screenshot%202023-07-25%20144507.png)
![output](/Screenshot%202023-07-25%20144536.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.