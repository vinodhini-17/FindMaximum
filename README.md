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
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
   a=max(marks)
   return a

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a
  
   


```
## Sample Input and Output
i)
![max in 1](https://github.com/vinodhini-17/FindMaximum/assets/145742741/b1f115db-8327-45f2-aa08-d6fc65851b3c)

ii)
![max2 in](https://github.com/vinodhini-17/FindMaximum/assets/145742741/20037044-8589-43b8-9e07-984d1d037941)

iii)
![max 3 in](https://github.com/vinodhini-17/FindMaximum/assets/145742741/4e7fb213-1d61-44f2-959d-f765b6520349)

## Output:
i)
![max1 out](https://github.com/vinodhini-17/FindMaximum/assets/145742741/00bd4bfc-988a-4d96-83e3-c5a46eb49836)

ii)
![max 2out](https://github.com/vinodhini-17/FindMaximum/assets/145742741/b9da550e-771a-4d3a-8064-c2588c1fb0b5)

iii)
![max 3 out](https://github.com/vinodhini-17/FindMaximum/assets/145742741/047dbf98-eea0-444e-91df-e777077a125b)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
