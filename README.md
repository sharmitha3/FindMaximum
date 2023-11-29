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
``` 
Program to mark the maximum of marks using the list method sort
Developed by: SHARMITHA V
RegisterNumber: 23002259
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: SHARMITHA V
RegisterNumber: 23002259
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res

```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: SHARMITHA V
RegisterNumber: 23002259
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```
## Sample Input and Output

![image](https://github.com/sharmitha3/FindMaximum/assets/145974496/bb67e06c-1424-473f-81c6-ac96940d1978)
![image](https://github.com/sharmitha3/FindMaximum/assets/145974496/7f48862f-feac-4dd9-abdb-ad50ec7a7eb3)
![image](https://github.com/sharmitha3/FindMaximum/assets/145974496/83ad5279-0c94-4e26-8f81-d6289a378a2c)


## Output:
![image](https://github.com/sharmitha3/FindMaximum/assets/145974496/6caccf01-2f04-429b-b950-64beedb2a18d)
![image](https://github.com/sharmitha3/FindMaximum/assets/145974496/caea1ccd-843f-49d5-bc9a-99be6777a365)
![image](https://github.com/sharmitha3/FindMaximum/assets/145974496/df9b2e33-d0fb-45d4-b6f5-3abc5f5f8da9)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
