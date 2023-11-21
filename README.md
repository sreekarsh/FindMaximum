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
    large=max(marks)
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
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i) ![image](https://github.com/sreekarsh/FindMaximum/assets/139841918/28966a91-e1f1-499e-b79c-7583485ba922)

ii) ![image](https://github.com/sreekarsh/FindMaximum/assets/139841918/b9b24f99-4094-437c-b783-9cb8875a8b7e)

iii) ![image](https://github.com/sreekarsh/FindMaximum/assets/139841918/e5e8dcfa-438c-4708-b720-942615d843fc)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
