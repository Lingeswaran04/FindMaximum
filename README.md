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
Developed by: LINGESWARAN K 
RegisterNumber: 212222110022
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
Developed by: LINGESWARAN K
RegisterNumber: 212222110022
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: LINGESWARAN K
RegisterNumber: 212222110022
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i)	# maximum of marks using the list method sort.
![image](https://github.com/Lingeswaran04/FindMaximum/assets/119103865/b964d261-1145-4e29-8898-8e4c48e943dc)

ii)	# maximum marks using the list method max().
![image](https://github.com/Lingeswaran04/FindMaximum/assets/119103865/b3539806-0ce3-4fd3-85ee-b431ca09845b)

iii) # maximum marks without using builtin functions.
![image](https://github.com/Lingeswaran04/FindMaximum/assets/119103865/a38c8783-5e1b-4681-8988-1bb44c4e55b3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
