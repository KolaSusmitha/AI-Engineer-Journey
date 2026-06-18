# DAY 2 - ADVANCED NUMPY

## Topics Covered

* Indexing
* Negative Indexing
* Slicing
* Matrix Slicing
* Broadcasting
* Vectorization
* AI Applications of Vectorization

---

## Indexing

Indexing is used to access specific elements in an array.

Example:

```python
arr = np.array([10,20,30,40,50])

arr[0]
```

Output:

```python
10
```

### Why It Is Used

* Access specific values quickly
* Retrieve features from datasets
* Select required data points

---

## Negative Indexing

Negative indexing starts from the end of an array.

Example:

```python
arr[-1]
```

Output:

```python
50
```

### Why It Is Used

* Access last elements efficiently
* Useful when dataset size is unknown

---

## Slicing

Slicing extracts a portion of an array.

Example:

```python
arr[1:4]
```

Output:

```python
[20,30,40]
```

### Why It Is Used

* Extract subsets of data
* Split datasets
* Select ranges of values

---

## Matrix Slicing

Matrix slicing is used to access specific rows and columns.

Example:

```python
matrix[:,0]
```

Output:

```python
[1,4,7]
```

### Why It Is Used

* Select features from datasets
* Extract rows and columns
* Data preprocessing

---

## Broadcasting

Broadcasting allows NumPy to perform operations on arrays with compatible shapes.

Example:

```python
arr + 10
```

Conceptually:

```python
[1,2,3]
+
[10,10,10]
```

Output:

```python
[11,12,13]
```

### Why It Is Used

* Simplifies calculations
* Eliminates unnecessary loops
* Improves code readability

---

## Vectorization

Vectorization performs operations on entire arrays without explicit Python loops.

Example:

```python
arr * 2
```

Output:

```python
[2,4,6,8]
```

### Why It Is Used

* Faster execution
* Efficient memory usage
* Optimized low-level implementation

---

## Difference Between Broadcasting and Vectorization

### Broadcasting

Makes array shapes compatible for mathematical operations.

### Vectorization

Performs operations on entire arrays efficiently without Python loops.

Example:

```python
arr * 5
```

Broadcasting:

* Scalar 5 becomes compatible with the array.

Vectorization:

* Multiplication is performed on all elements efficiently.

---

## AI Connection

These concepts are heavily used in:

* Data preprocessing
* Feature engineering
* Machine Learning pipelines
* Deep Learning
* Computer Vision
* Natural Language Processing

Example:

```python
pixels / 255
```

Broadcasting:

* 255 is applied to all pixels.

Vectorization:

* All pixel values are processed efficiently.

---

## Key Takeaways

* Indexing accesses specific elements.
* Slicing extracts subsets of data.
* Matrix slicing helps access rows and columns.
* Broadcasting makes shapes compatible.
* Vectorization performs fast array-wide operations.
* Efficient AI systems rely heavily on vectorized computation.

---

## Summary

Advanced NumPy operations enable efficient handling of large datasets. Broadcasting and vectorization are fundamental concepts used in modern AI systems to perform computations quickly and efficiently.
