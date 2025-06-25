# Data Structures - Core Concepts

## What is a Data Structure?

A **data structure** is a way to organize, store, and access data in memory so you can use it efficiently for specific operations.

## Why Data Structures Matter

Think of it like organizing your closet. You could throw everything in a pile (works, but finding anything takes forever), or organize by type, season, color, etc. Different organization methods optimize for different needs - quick access, easy additions, space efficiency.

## Core Properties

Every data structure has trade-offs across:

### Time Complexity

How fast can you:

- **Access** an element
- **Search** for a value
- **Insert** new data
- **Delete** data

### Space Complexity

How much memory does it use, including overhead?

### Operations Supported

What can you actually do with it?

## Categories

### Linear Structures

Elements in sequence

- Arrays
- Linked Lists
- Stacks
- Queues

### Non-linear Structures

Hierarchical or networked relationships

- Trees
- Graphs
- Hash Tables

### Abstract vs Concrete

- **Abstract** = concept (like "Stack" - LIFO behavior)
- **Concrete** = actual implementation (array-based stack vs linked-list-based stack)

## JavaScript Context

JS gives you several built-in structures:

- **Array**: Dynamic, can hold mixed types
- **Object**: Hash table essentially
- **Map/Set**: Newer, more predictable than objects
- **String**: Immutable sequence

But you'll implement others (linked lists, trees) using these primitives.

## The Big Picture

Data structures aren't just academic - they're optimization tools. Choosing the right one can turn an O(n²) algorithm into O(log n). That's the difference between 1 second and 17 minutes on 10,000 items.

## Interview Notes

### Key Talking Points

- Always consider time/space trade-offs
- Know when to use built-in JS structures vs custom implementations
- Understand that most complex structures are built from primitives
- Real-world applications matter more than just knowing definitions

### Common Follow-ups

- "When would you choose X over Y?"
- "What's the space complexity of this approach?"
- "How would you optimize this for [specific use case]?"
