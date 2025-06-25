# Algorithms - Core Concepts

## What is an Algorithm?

An **algorithm** is a step-by-step procedure or set of rules for solving a specific problem or performing a computation. It's a finite sequence of well-defined instructions that takes input and produces output.

## Key Characteristics

### Finiteness

Must terminate after a finite number of steps

### Definiteness

Each step must be precisely defined and unambiguous

### Input

Zero or more inputs (data the algorithm works with)

### Output

At least one output (the result)

### Effectiveness

Each step must be basic enough to be carried out by a person with paper and pencil

## Algorithm vs Program vs Function

- **Algorithm**: The abstract concept/logic (like a recipe)
- **Program**: Algorithm implemented in a specific language
- **Function**: Code unit that may implement an algorithm

Example: "Find the maximum value in a list" is an algorithm concept. Your JavaScript function `findMax()` is the implementation.

## Algorithm Design Paradigms

### Brute Force

Try all possible solutions

- Simple but often inefficient
- Good for small inputs or when optimization isn't critical

### Divide and Conquer

Break problem into smaller subproblems

- Merge Sort, Quick Sort, Binary Search
- Often leads to O(log n) or O(n log n) solutions

### Dynamic Programming

Store solutions to subproblems to avoid recomputation

- Fibonacci, knapsack problems
- Trade space for time

### Greedy

Make locally optimal choices at each step

- Doesn't always give global optimum
- Dijkstra's algorithm, Huffman coding

### Backtracking

Try solutions and undo if they don't work

- N-Queens, Sudoku solver
- Systematic trial and error

## Complexity Analysis

### Time Complexity

How execution time grows with input size

- Best case, average case, worst case
- Big O notation: O(1), O(log n), O(n), O(n log n), O(n²), O(2ⁿ)

### Space Complexity

How much memory the algorithm uses

- Input space vs auxiliary space
- In-place vs out-of-place algorithms

### Trade-offs

Often you can trade time for space or vice versa

## JavaScript-Specific Considerations

### Built-in Methods

JS provides many algorithmic operations:

```javascript
// These are algorithms under the hood
arr.sort(); // Usually Timsort (hybrid merge/insertion)
arr.find(); // Linear search
arr.includes(); // Linear search
arr.map(); // Transformation algorithm
```

### Performance Quirks

- V8 engine optimizations
- Array vs object performance characteristics
- Function call overhead in recursive algorithms

### Memory Management

- Garbage collection affects space complexity
- Closures can create memory leaks in recursive algorithms
- Stack overflow considerations

## Categories of Algorithms

### By Purpose

- **Searching**: Find specific data
- **Sorting**: Arrange data in order
- **Graph**: Navigate relationships
- **String**: Text processing
- **Mathematical**: Computations

### By Approach

- **Iterative**: Use loops
- **Recursive**: Function calls itself
- **Parallel**: Multiple operations simultaneously

## Real-World Applications

### Search Engines

Complex ranking and retrieval algorithms

### Social Media

Timeline algorithms, recommendation systems

### Navigation

Route-finding algorithms (Dijkstra, A\*)

### Compression

Data compression algorithms

### Machine Learning

Training algorithms, neural networks

## Interview Notes

### Key Talking Points

- Always analyze time and space complexity
- Discuss trade-offs between different approaches
- Consider edge cases and input constraints
- Explain your thought process step by step
- Know when to use iterative vs recursive solutions

### Common Questions

- "Can you optimize this further?"
- "What's the worst-case scenario?"
- "How would this scale with larger inputs?"
- "What are alternative approaches?"

### Red Flags to Avoid

- Jumping to code without understanding the problem
- Not considering edge cases
- Ignoring complexity analysis
- Not explaining your reasoning

## The Bottom Line

Algorithms are tools for solving problems efficiently. The best algorithm depends on your constraints: input size, memory limits, readability requirements, and performance needs. Master the fundamentals, understand the trade-offs, and you can tackle any problem systematically.
