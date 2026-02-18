

# Space Complexity of Arrays Theory

This repository serves as a comprehensive theoretical guide on the **Space Complexity** of array data structures. It details how memory allocation works for arrays of various dimensions (1D, 2D, and 3D) and distinguishes between fixed, variable, and auxiliary space requirements.

## 📖 Overview

Space complexity is a measure of the amount of working storage an algorithm needs. This repository specifically focuses on:

* **Input Space:** Space used by the input components.
* **Auxiliary Space:** Extra or temporary space used by an algorithm.
* **Dimensionality:** How increasing array dimensions affects memory usage (Linear vs. Quadratic vs. Cubic).

## 🗂 Repository Contents

* **`README.md`**: Theoretical explanations and formulas.
* **`1.Space Complexity of Array Operation.pdf`**: A detailed document covering array operations and their complexities.

---

## 🧠 Key Concepts

### 1. Auxiliary vs. Input Space

The total space complexity is the sum of the space required for the fixed component (constants, simple variables) and the variable component (dependent on instance characteristics).

* **Input Space:** The memory required to store the input data itself.
* **Auxiliary Space:** The extra space or temporary memory used by the algorithm during its execution.

### 2. One-Dimensional Arrays

For simple assignments and 1D arrays, if we are merely accessing or assigning single elements, the operation often takes constant auxiliary space.

**Example:**

```cpp
a[1] = 1; // O(1) Space
a[2] = 2; // O(1) Space
...
a[5] = 5; // O(1) Space

```

* **Complexity:**  (Constant)
* **Note:** We are not reusing space; rather, we are utilizing allocated slots. If allocating an entire array of size , the space complexity is .

### 3. Two-Dimensional Arrays

For a 2D array (matrix) with dimensions :

* **Formula:** 
* **Square Matrix:** If  and , then .
* **Complexity:**  (Quadratic)

### 4. Three-Dimensional Arrays

The space complexity of a 3D array depends on its dimensions ( rows,  columns,  depth) and the data type size.

**Standard Calculation:**
If each element occupies a fixed amount of space:

* **Space:** 
* **Complexity:** 

**Special Cases:**

1. **Cubic Dimensions:** If :
* **Complexity:**  (Cubic)


2. **Variable Element Size:** If the size of each element varies (e.g., objects of size ):
* **Complexity:** 



> **Note:** Space complexity calculations here account for the storage of the array itself. They do not include auxiliary structures used by external functions operating on these arrays.

---

## 🚀 Getting Started

To study the materials in this repository:

1. **Clone the repository:**
```bash
git clone https://github.com/AvinandanBose/Space_Complexity_Of_Arrays_Theory.git

```


2. **Read the PDF:** Open `1.Space Complexity of Array Operation.pdf` for a deep dive into the operations.
3. **Review the Notes:** Read through the theoretical breakdowns provided in this README.

## 🤝 Contributing

Contributions are welcome! If you have additional theoretical insights, corrections, or code examples demonstrating these complexities, feel free to fork the repository and submit a pull request.

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

---

*Created by [Avinandan Bose*](https://github.com/AvinandanBose)
