# Sorting_Algorithms_Benchmark
Ritage Adel altarhoney 3166279
Sorting-Algorithms-Benchmark
1. Student Information
Name: عبدالحميد جلال باباني__
University ID: 3167052__________
Section: A________
2. Description
A Java program that measures the execution time (in microseconds, using System.nanoTime()) of five sorting algorithms (Selection, Insertion, Bubble, Merge, Quick) on arrays of N = 100,000 integers in four cases: Random, Reversed, Partially Sorted (~80%), and Fully Sorted. Each algorithm runs on an independent copy of the data, and only the sorting time is measured (copying is excluded).

Run it with: javac SortingBenchmark.java && java SortingBenchmark

3. Results (microseconds)
Algorithm	Random	Reversed	Partially Sorted	Fully Sorted
Selection Sort	3,523,390	3,202,959	1,869,560	1,867,633
Insertion Sort	1,620,037	3,250,266	130,708	95
Bubble Sort	16,172,723	8,046,609	7,226,092	29
Merge Sort	63,858	32,195	8,747	8,017
Quick Sort	13,502	2,997,858	6,242	3,797,811
Exact values vary from one machine/run to another; the trends stay the same.
