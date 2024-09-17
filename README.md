Why NumPy?
You can do numerical calculations using pure Python. In the beginning, you might think Python is fast but once your data gets large, you'll start to notice slow downs.
One of the main reasons you use NumPy is because it's fast. Behind the scenes, the code has been optimized to run using C. Which is another programming language, which can do things much faster than Python.
The benefit of this being behind the scenes is you don't need to know any C to take advantage of it. You can write your numerical computations in Python using NumPy and get the added speed benefits.
If your curious as to what causes this speed benefit, it's a process called vectorization. Vectorization aims to do calculations by avoiding loops as loops can create potential bottlenecks.
NumPy achieves vectorization through a process called broadcasting.

What does this notebook cover?
The NumPy library is very capable. However, learning everything off by heart isn't necessary. Instead, this notebook focuses on the main concepts of NumPy and the ndarray datatype.
You can think of the ndarray datatype as a very flexible array of numbers.
More specifically, we'll look at:
NumPy datatypes & attributes
Creating arrays
Viewing arrays & matrices (indexing)
Manipulating & comparing arrays
Sorting arrays
Use cases (examples of turning things into numbers)
After going through it, you'll have the base knolwedge of NumPy you need to keep moving forwar
