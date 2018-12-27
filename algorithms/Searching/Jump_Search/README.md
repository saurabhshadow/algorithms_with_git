# Jump Search

<p>Like Binary Search, Jump Search is a searching algorithm for sorted arrays. The basic idea is to check fewer elements (than linear search) by jumping ahead by fixed steps or skipping some elements in place of searching all elements.

For example, suppose we have an array arr[] of size n and block (to be jumped) size m. Then we search at the indexes arr[0], arr[m], arr[2m]…..arr[km] and so on. Once we find the interval (arr[km] < x < arr[(k+1)m]), we perform a linear search operation from the index km to find the element x.</p>


### Input Format

- Enter the size of array(n).
- Enter the array in sorted form according to given size.
- Enter the element to be searched(x).

### Output Format

- Prints a single line the number x is located at the index.

### Sample Input

```sh
5
1 2 3 4 5
3
```
### Sample Output

```sh
3 is located at index 2
```

### Implemented in:

- [C](Jump_search.c)
- [C++](Jump_search.cpp)
