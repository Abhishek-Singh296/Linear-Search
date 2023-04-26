# Linear-Search
Linear Search is defined as a sequential search algorithm that starts at one end and goes through each element of a list until the desired element is found, otherwise the search continues till the end of the data set.

--- 

## __Working__
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
#include <stdio.h>
 
int search(int arr[], int N, int x)
{
    int i;
    for (i = 0; i < N; i++)
        if (arr[i] == x)
            return i;
    return -1;
}
 
// Driver code
int main(void)
{
    int arr[] = { 2, 3, 4, 10, 40 };
    int x = 10;
    int N = sizeof(arr) / sizeof(arr[0]);
 
    // Function call
    int result = search(arr, N, x);
    (result == -1)
        ? printf("Element is not present in array")
        : printf("Element is present at index %d", result);
    return 0;
}
```

## __Output__

![Screenshot 2023-04-26 090458](https://user-images.githubusercontent.com/113619312/234465014-2346f5ac-3ef5-4e0e-84ac-d891917d1862.png)

---
