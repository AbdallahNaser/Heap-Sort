# Heap Sort Implementation

This repository contains the implementation of the **Heap Sort** algorithm, a comparison-based sorting technique based on a Binary Heap data structure.

## Overview
Heap Sort is an efficient sorting algorithm with the following key characteristics:

- **Time Complexity:**
  - Best Case: O(n log n)
  - Average Case: O(n log n)
  - Worst Case: O(n log n)
- **Space Complexity:** O(1) (in-place sorting)
- **Algorithm Type:** Comparison-based, in-place

## Features
- Implemented in **C++**.
- Supports sorting arrays/lists of integers, floats, or other comparable data types.
- Includes a max-heap and min-heap variant of the algorithm.

## File Structure
- `heap_sort.cpp`: Contains the implementation of Heap Sort.
- `README.md`: Documentation for the repository.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heap-sort.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd heap-sort
   ```
3. Compile the code:
   ```bash
   g++ -o heap_sort heap_sort.cpp
   ```
4. Run the executable:
   ```bash
   ./heap_sort
   ```

## Algorithm Steps
1. Build a max heap from the input data.
2. Extract the largest element (root of the heap) and swap it with the last element.
3. Reduce the heap size and heapify the root element.
4. Repeat steps 2 and 3 until the heap size is 1.

## Example Input and Output
### Input
```plaintext
Array: [4, 10, 3, 5, 1]
```
### Output
```plaintext
Sorted Array: [1, 3, 4, 5, 10]
```

## Contributing
Contributions are welcome! Feel free to fork the repository, create a branch, and submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## About Me
I am Abdallah Naser ,backend developer , frontend using Reactjs,and I'm a skilled WordPress Designer/Developer with extensive
 experience in creating and customizing websites using WordPress, Elementor, and WooCommerce.
---

For any questions or feedback, please feel free to contact me!
