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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large=marks[len(marks)-1]
    marks.sort(reverse=True)
    large=marks[0]
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(marks):
    maxmark=0
    for i in marks:
        if i>maxmark:
            maxmark=i
    return maxmark

```
## Output:
i)	# To find the maximum of marks using the list method sort.

![Screenshot 2024-04-01 130323](https://github.com/ligneshwar/FindMaximum/assets/149365037/3a440407-dbb9-4cfa-b38f-244588827837)

ii)	# To find the maximum marks using the list method max().
![Screenshot 2024-04-01 130358](https://github.com/ligneshwar/FindMaximum/assets/149365037/d106509a-d974-4156-9bd7-4c1798239f43)

iii) # To find the maximum marks without using builtin functions.
![Screenshot 2024-04-01 130415](https://github.com/ligneshwar/FindMaximum/assets/149365037/3b8d5ed1-0b57-4788-a544-817ab22bb0bc)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
