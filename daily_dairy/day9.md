**DAY 9(03/07/2025)**

Today i learned about the NumPy library and its various functions in detail.

1) **NumPy(Numerical Python):** It is a powerful library used for numerical computations in Python.

   i. **Advantages of NumPy over Lists** - NumPy supports faster and more efficient mathematical operations than Python lists.

   ii. **Performance Comparison** - We used process_time() to compare execution time between a list operation and a NumPy operation. NumPy was significantly faster.
   
   iii.**Numpy Arrays** - We learned to create 1-D and 2-D NumPy arrays. 

   iv. **Initial Placeholders in NumPy arrays** - **np.zeros()** is used to create an array with all values as 0, **np.ones()** is used to create an array with all values as 1, **np.full()** is used to create an array with a specified value, **np.eye()** is used to create an identity matrix.

    v. **Creating a NumPy array with random values** - **np.random.random()** is used to create an array with random float values between 0.0 and 1.0 and **np.random.randint()** is used to create an array with random integer values between a given range.

   vi. **Creating array of evenly spaced values** - **np.linspace(start, stop, num_values)** returns an array of evenly spaced values between start and stop, divided into the specified number of values. **np.arange(start, stop, step)** returns an array of values from start to stop with a defined step interval.

   vii. **Converting a list to a NumPy array** - **np.asarray(list_name)** is used to convert a list to a NumPy array.

   viii. **Array Properties** - **.shape** returns the dimensions (rows, columns) of the array.
   **.ndim** returns the number of dimensions (axes) of the array.
   **.size** returns the total number of elements in the array.
   **.dtype** returns the data type of the array’s elements (e.g., int, float).

   ix. **Mathematical Operations on NumPy arrays** - It is not possible to perform element-wise operations in a list as the "+" operation concatenated two lists. However, in a NumPy array, element-wise operations are possible. The functions - np.add(), np.subtract(), np.multiply(), np.divide() are used to add, subtract, multiply and divide two NumPy arrays respectively.

   x. **Array Manipulation** - We can find the transpose of array using **.T** and **np.transpose()**.  We can reshape an array using **.reshape(new_shape)**.
