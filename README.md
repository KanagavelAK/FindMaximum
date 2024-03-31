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
def max_marks (marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    max_marks = 0
    for i in marks:
        if i > max_marks:
            max_marks = i
    return (max_marks)


```



## Output:
Using sort()
![Screenshot 2024-03-31 130039](https://github.com/KanagavelAK/FindMaximum/assets/151514454/0921627d-c735-4477-960a-9970ce55c9eb)
Using max()
![Screenshot 2024-03-31 130055](https://github.com/KanagavelAK/FindMaximum/assets/151514454/6f3cb197-156b-45e9-aa72-17764aa90eb3)
Without using built-in functions
![Screenshot 2024-03-31 130111](https://github.com/KanagavelAK/FindMaximum/assets/151514454/ab69a65f-beb6-42b6-89c6-58c261bca4ed)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
