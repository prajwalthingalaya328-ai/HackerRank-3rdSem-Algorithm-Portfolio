# HackerRank 3rd Semester Algorithm Portfolio

## Student Information

* Name: Prajwal N Thingalaya
* USN: R25EF188
* Semester: 3rd Semester
* Branch: Computer Science and Engineering
* University: REVA University
* Programming Language: C++

## Portfolio Links

* HackerRank Profile: https://www.hackerrank.com/
* GitHub Repository: https://github.com/prajwalthingalaya328-ai/HackerRank-3rdSem-Algorithm-Portfolio

## Introduction

This repository contains my solutions for five algorithmic problems completed as part of my 3rd semester programming practice. The problems cover array processing, searching, sorting, counting, and greedy techniques.

All solutions were implemented in C++ and tested on HackerRank. The repository also contains screenshots as evidence of the completed submissions.

## Problems Completed

### 1. Mini-Max Sum

Challenge: https://www.hackerrank.com/challenges/mini-max-sum/problem

Approach:

* Read five integers.
* Calculate their total sum.
* Identify the minimum and maximum values.
* Minimum sum is obtained by excluding the maximum value.
* Maximum sum is obtained by excluding the minimum value.

Time Complexity: O(N)

Auxiliary Space: O(1)

Evidence:

* [Screenshot 1](Evidence/01-Mini-Max-Sum/01-Mini-Max-Sum-1.png.png)
* [Screenshot 2](Evidence/01-Mini-Max-Sum/01-Mini-Max-Sum-2.png.png)
* [Screenshot 3](Evidence/01-Mini-Max-Sum/01-Mini-Max-Sum-3.png.png)

### 2. Birthday Cake Candles

Challenge: https://www.hackerrank.com/challenges/birthday-cake-candles/problem

Approach:

* Read the candle heights.
* Find the maximum candle height.
* Count how many candles have that maximum height.
* Return the count.

Time Complexity: O(N)

Auxiliary Space: O(1)

Evidence:

* [Screenshot 1](Evidence/02-Birthday-Cake-Candles/02-Birthday-Cake-Candles-1.png)
* [Screenshot 2](Evidence/02-Birthday-Cake-Candles/02-Birthday-Cake-Candles-2.png)
* [Screenshot 3](Evidence/02-Birthday-Cake-Candles/02-Birthday-Cake-Candles-3.png)

### 3. Insertion Sort Part 1

Challenge: https://www.hackerrank.com/challenges/insertionsort1/problem

Approach:

* Store the last element as the value to be inserted.
* Compare it with the elements before it.
* Shift larger elements one position to the right.
* Insert the stored value into its correct position.
* Print the array after each shift as required.

Time Complexity: O(N)

Auxiliary Space: O(1)

Evidence:

* [Screenshot 1](Evidence/03-Insertion-Sort-Part-1/03-Insertion-Sort-Part-1-1.png)
* [Screenshot 2](Evidence/03-Insertion-Sort-Part-1/03-Insertion-Sort-Part-1-2.png)
* [Screenshot 3](Evidence/03-Insertion-Sort-Part-1/03-Insertion-Sort-Part-1-3.png)

### 4. Binary Search

Approach:

* Use a sorted array.
* Set low and high boundaries.
* Calculate the middle element.
* Compare the middle element with the target.
* Reduce the search range according to the comparison.
* Continue until the element is found or the range becomes empty.

Time Complexity: O(log N)

Auxiliary Space: O(1)

Evidence:

* [Screenshot 1](Evidence/04-Binary-Search/04-Binary-Search-1.png)
* [Screenshot 2](Evidence/04-Binary-Search/04-Binary-Search-2.png)
* [Screenshot 3](Evidence/04-Binary-Search/04-Binary-Search-3.png)

### 5. Mark and Toys

Challenge: https://www.hackerrank.com/challenges/mark-and-toys/problem

Approach:

* Sort the toy prices in ascending order.
* Start buying from the cheapest toy.
* Keep adding prices while the total stays within the budget.
* Stop when the next toy cannot be purchased.
* Count the maximum number of toys purchased.

Time Complexity: O(N log N)

Auxiliary Space: O(log N)

Evidence:

* [Screenshot 1](Evidence/05-Mark-and-Toys/05-Mark-and-Toys-1.png)
* [Screenshot 2](Evidence/05-Mark-and-Toys/05-Mark-and-Toys-2.png)
* [Screenshot 3](Evidence/05-Mark-and-Toys/05-Mark-and-Toys-3.png)

## Complexity Summary

| Problem               | Time Complexity | Space Complexity |
| --------------------- | --------------- | ---------------- |
| Mini-Max Sum          | O(N)            | O(1)             |
| Birthday Cake Candles | O(N)            | O(1)             |
| Insertion Sort Part 1 | O(N)            | O(1)             |
| Binary Search         | O(log N)        | O(1)             |
| Mark and Toys         | O(N log N)      | O(log N)         |

## Repository Structure

```text
HackerRank-3rdSem-Algorithm-Portfolio/
│
├── README.md
│
├── 01-Mini-Max-Sum/
│   └── solution.cpp
│
├── Evidence/
│   ├── 01-Mini-Max-Sum/
│   ├── 02-Birthday-Cake-Candles/
│   ├── 03-Insertion-Sort-Part-1/
│   ├── 04-Binary-Search/
│   └── 05-Mark-and-Toys/
│
└── ...
```

## Skills Practiced

* Arrays
* Sorting
* Searching
* Iteration
* Greedy Algorithms
* Basic Algorithm Analysis
* Time and Space Complexity
* C++ Programming
* GitHub Repository Management
* HackerRank Problem Solving

## Reflection

Completing these five problems helped me improve my understanding of basic algorithms and problem-solving techniques. I practiced working with arrays, sorting, searching, counting, and greedy approaches. I also learned how to analyze the time and space complexity of an algorithm instead of focusing only on getting the correct output.

The problems helped me understand how different approaches affect efficiency. For example, Binary Search reduces the search space by half at every step, while sorting-based solutions can be useful when the problem requires processing elements in an ordered manner.

Creating this GitHub portfolio also helped me understand how to organize programming solutions professionally. I learned how to maintain separate folders for different problems, upload evidence, and document the approach and complexity of each solution. Overall, this activity improved both my coding practice and my ability to present programming work in a structured way.

## Conclusion

This portfolio demonstrates my practice with fundamental algorithms using C++. The five completed problems provide experience with arrays, sorting, searching, counting, and greedy problem-solving. The repository contains the solutions, complexity analysis, and submission evidence for reference.
