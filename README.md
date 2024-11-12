## Vector dot product

>This repository contains code for two different *ways* to perform dot product.

## Formula for dot product
```math
d = \vec{A}.\vec{B} 
```

### Code Snippets

1 **python**
  ```
import numpy as np

# Creating two numpy One-Dimensional array using the array() method
arr1 = np.array([2+3j,5+6j])
arr2 = np.array([9+10j,11+12j])

# Display the arrays
print("Array1...\n",arr1)
print("\nArray2...\n",arr2)

# Check the Dimensions of both the arrays
print("\nDimensions of Array1...\n",arr1.ndim)
print("\nDimensions of Array2...\n",arr2.ndim)

# Check the Shape of both the arrays
print("\nShape of Array1...\n",arr1.shape)
print("\nShape of Array2...\n",arr2.shape)

# To return the dot product of two vectors, use the numpy.vdot() method in Python.
print("\nResult...\n",np.vdot(arr1, arr2)) 
```
 
2 **cpp**
```
#include <iostream>
#include <vector>
#include <numeric>
using namespace std;

int main() {
    vector<int> v1 = {2, 3, 1};
    vector<int> v2 = {4, 2, 5};

    int dotProduct = inner_product(v1.begin(), v1.end(), v2.begin(), 0);

    cout << "Dot product: " << dotProduct << endl;

    return 0;
}
```
![alt text](https://cdn1.byjus.com/wp-content/uploads/2022/09/Dot-Product-Of-Two-Vectors-2.png)

## Link to documentry of dot product:
[dot product](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://math.libretexts.org/Bookshelves/Calculus/Calculus_(OpenStax)/12%253A_Vectors_in_Space/12.03%253A_The_Dot_Product&ved=2ahUKEwj0zNOGw9aJAxWgVWwGHZDZCk4QFnoECDAQAQ&usg=AOvVaw09J8VtZi14LsBb23pNVRw0)

## Comparison between two methods:->

|| cpp | python |
|---|---|---|
|lines of code|more lines of code|fewer lines of code|
|memory used|static| dynamic|
|time | O(n)|O(n)|

## Our Courses
- maths class 10th
- maths class 12th

### topics covered
- [x] jee
- [x] boards

## License
License is provided with repository to commit changes[^1]
[^1]: MIT License
  :The MIT License is a permissive software license originating at the Massachusetts Institute of Technology (MIT)[6] in the late 1980s.[7] As a permissive license, it puts very few restrictions on reuse and therefore has high license compatibility.[8][9]
 
## Copyright
>[!WARNING]
>Using content for commercial purposes will cause copyright issues

