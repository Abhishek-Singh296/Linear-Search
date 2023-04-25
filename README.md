# Linear-Search
Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.

--- 

## __ Working__
The following steps are followed to search for an element k = 1 in the list below.

![image](https://user-images.githubusercontent.com/113619312/234359169-f786cca1-c8e1-4856-a107-25932e2d0ffc.png)

1.Start from the first element, compare k with each element x.

![image](https://user-images.githubusercontent.com/113619312/234359288-d155338c-5862-479e-a6a2-73e22fe8cf08.png)

2.If x == k, return the index.

![image](https://user-images.githubusercontent.com/113619312/234359373-bbf523fd-b7a4-4d05-9fa6-240a4ad347bc.png)

3.Else, return not found.

---

## __Algorithm__
Step 1: First, read the search element (Target element) in the array.
Step 2: Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.
Step 3: Match the key with arr[i].
Step 4: If the key matches, return the index. Otherwise, increment i by 1.

## __Code__
```
