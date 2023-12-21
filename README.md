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
Developed by: Panduru somu 
RegisterNumber: 23005083
'''
def max_marks(marks):
   marks.sort()
   return marks[-1]
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max = list1[0]
    for i in range(1,len(list1)):
        if(max<list1[i]):
            max = list1[i]
    return max
```
## Sample Input and Output
## Output:

![Screenshot 2023-12-21 202547](https://github.com/Pandurusomu/FindMaximum/assets/148988619/7673cd7f-7abb-4711-ad73-3d08241fd254)

![Screenshot 2023-12-21 202716](https://github.com/Pandurusomu/FindMaximum/assets/148988619/57c06954-699e-4936-a036-025bd239fb82)


![image](https://github.com/Pandurusomu/FindMaximum/assets/148988619/cb44efb3-c7c0-4f4a-a830-180646f70ae8)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
