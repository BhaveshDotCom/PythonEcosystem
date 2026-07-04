# Numpy

NumPy (Numerical Python) is the foundational library for scientific computing in Python. It provides high-performance, multi-dimensional array objects (ndarray) and optimized tools for vectorization and broadcasting. It is the bedrock for data science and machine learning libraries like Pandas, SciPy, and Scikit-Learn

Data Types: NumPy arrays only store one data type (homogeneous). Python lists can store multiple data types (heterogeneous) in a single list.

Memory Efficiency: NumPy arrays store data in a single continuous block of memory. Python lists store an array of pointers to objects scattered across memory, which uses much more space.

Performance Speed: NumPy operations run in optimized C code, making them vastly faster than lists. Python lists require slow loops for element-by-element operations.

Mathematical Operations: NumPy allows vectorised operations (e.g., array * 2 multiplies every number). Python lists do not support this directly (e.g., list * 2 duplicates the list instead).

Functionality: NumPy provides built-in tools for linear algebra, matrices, and statistics. Python lists only have basic methods like appending, removing, and sorting.