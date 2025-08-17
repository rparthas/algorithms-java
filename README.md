# Algorithms in Java

This repository contains a collection of Java implementations of various algorithms and data structures. It's a personal project for learning and practicing algorithm design and implementation.

## Project Structure

The project is organized into several packages, each focusing on a specific area of algorithms or data structures.

*   `src/algorithms`: Contains implementations of fundamental algorithms and data structures, including:
    *   `adt`: Abstract Data Types like Stacks, Queues, and Priority Queues.
    *   `search`: Search algorithms and data structures like Binary Search and BST.
    *   `sorting`: Various sorting algorithms like Merge Sort, Quick Sort, and Heap Sort.
    *   `unionfind`: Union-Find data structure implementations.
*   `src/amazon`: Contains solutions to programming problems that are likely from Amazon interviews.
*   `src/com/businesshouse`: A simple board game implementation.
*   `src/edu/learn/executor`: A custom executor service implementation.
*   `src/java8/fpj`: Examples demonstrating functional programming concepts in Java 8.
*   `src/learn`: Contains solutions to problems from various online learning platforms, such as:
    *   `cci`: Cracking the Coding Interview
    *   `edx`: edX
    *   `hk`: HackerRank
    *   `techgig`: TechGig
*   `src/sorting`: Contains another set of sorting algorithm implementations.

## How to Use

This project uses Apache Maven as its build tool. You can build the project by running the following command from the root directory:

```bash
mvn clean install
```

## Dependencies

The project has the following dependency:

*   [log4j](https://logging.apache.org/log4j/1.2/): A library for logging.