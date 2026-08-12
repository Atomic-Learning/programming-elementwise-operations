In programming, an elementwise operation is an operation that is applied to each corresponding pair of elements in two data structures, such as arrays or lists. This means that the same operation is performed on each pair of elements, resulting in a new data structure containing the results of these operations.

For example, consider the creation of two arrays, `A` and `B`, each containing three elements which are then added together:

```
A = [1, 2, 3]
B = [4, 5, 6]
C = A + B  # This will result in C = [5, 7, 9]
```

In the example above, `C` is a new array that is created. The first entry in `C` is the sum of the first entries in `A` and `B`, the second entry in `C` is the sum of the second entries in `A` and `B`, and so on. This is an example of an elementwise operation.

# Corresponding Shape

Elementwise operations can normally only be performed on data structures that have the same shape. This means that the two data structures must have the same number of elements in each dimension. If the shapes of the two data structures do not match, an error will generally occur. The output of an elementwise operation will have the same shape as the input data structures.

The example below would typically generate some sort of error (assuming `+` is elementwise for the data structure in question), as the two arrays do not have the same shape:

```
A = [1, 2, 3]
B = [4, 5]
C = A + B  # This will result in an error due to shape mismatch
```