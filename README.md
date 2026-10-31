# Sorting Algorithms Benchmark

## Personal Information
- **Name:** رتاج عادل الترهوني 
- **Student ID:** 3166279
- **Section / Group:** B

## Project Description
This project compares the performance of 5 sorting algorithms on an array of size **N = 100,000**.

### Algorithms
| Complexity | Algorithms |
|---|---|
| O(N²) | Selection Sort, Insertion Sort, Bubble Sort |
| O(N log N) | Merge Sort, Quick Sort |

### Test Cases
1. **Random** – unsorted random numbers  
2. **Reverse** – sorted from largest to smallest  
3. **Partial** – about 80% sorted  
4. **Sorted** – fully sorted ascending  

### Timing Method
- Time is measured using `System.nanoTime()`
- Result is converted to microseconds: `(end - start) / 1000`
- The original array is copied before each test using `Arrays.copyOf`
- Only sorting time is measured (not array creation)


