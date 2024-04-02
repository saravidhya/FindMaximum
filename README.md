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
    large= max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
    
```



## Output:
i)	# To find the maximum of marks using the list method sort.

![Screenshot 2024-04-02 133306](https://github.com/saravidhya/FindMaximum/assets/87062069/f3c15f36-a365-42ef-bb1b-bdcc5ba19b7d)

ii)	# To find the maximum marks using the list method max().

![Screenshot 2024-04-02 133325](https://github.com/saravidhya/FindMaximum/assets/87062069/21ee9cb9-3f12-4080-b84e-6601a975de23)

iii) # To find the maximum marks without using builtin functions.

![Screenshot 2024-04-02 133409](https://github.com/saravidhya/FindMaximum/assets/87062069/ae58c0d2-f2df-40a1-b522-ef737028ea8a)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
