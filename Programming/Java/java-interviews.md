# Interview questions and answers

## Java Basics
*  **fail-fast and fail-safe**
    * fail-fast fails when the collection is been modified at the iteration time
* **Store sensitive data on character array instead of a String**
    * This is because the string is storage on the String pool and can be accesed until the GC cleans up.
* **When Finally block is not executed?**
    * If you call System.exit()
* **StringBuilder vs StringBuffer**
    * StringBuffer has synchronized methods(lenght, append..)
    * StringBuilder is faster and 99% of the times is considered bad practice use StringBuffer
* **Heap and Stack Memory**
    *Pending explanation
* **Transient**
    * Is a variable that won't be serialized.
* **Static binding vs dynamic binding.**
    * Need to find a better explanation
* **

## Data structures [Read More](https://hackernoon.com/50-data-structure-and-algorithms-interview-questions-for-programmers-b4b1ac61f5b0)

### List
* **Which list implementations is faster?**
    * LinkedList, implementations that use arrays are slower the the shifted and the last position added.
* **What differences exist between Iterator and ListIterator?**
    * An Iterator can be used to traverse the Set and List collections, while the ListIterator can be used to iterate only over Lists.
    * The Iterator can traverse a collection only in the forward direction, while the ListIterator can traverse a List in both directions.
    * The ListIterator implements the Iterator interface and contains extra functionality, such as adding an element, replacing an element, getting the index position for previous and next elements, etc.

### Maps
* **What is the difference between HashMap and Hashtable?**
    * HashMap allows null keys and values
    * Hastable is syncronized and HashMap not. HashMap is preferred for single threaded environments
    * HashMap can be iterated over its set of keys and is fail-fast
    * Hashtable is considered legacy class


### Arrays
1. How do you find the missing number in a given integer array of 1 to 100?
2. How do you find the duplicate number on a given integer array?
3. How do you find the largest and smallest number in an unsorted integer array?
4. How do you find all pairs of an integer array whose sum is equal to a given number?
5. How do you find duplicate numbers in an array if it contains multiple duplicates?
6. How are duplicates removed from a given array in Java?
7. How is an integer array sorted in place using the quicksort algorithm?
8. How do you remove duplicates from an array in place?
9. How do you reverse an array in place in Java?
10. How are duplicates removed from an array without using any library?

## Threads

## Completable futures

## Performance

## Algorthims

### Sorts algorithms
 Complexity of each algorithm:
|Algorithm|	Best |Average |Worst |
|-------|--------|----------|-----|
|Selection Sort|	Ω(n^2)|	θ(n^2)|	O(n^2)
|Bubble Sort	|Ω(n)|	θ(n^2)|	O(n^2)
|Insertion Sort|	Ω(n)|	θ(n^2)|	O(n^2)
|Heap Sort|	Ω(n log(n))|	θ(n log(n))|	O(n log(n))
|Quick Sort|	Ω(n log(n))|	θ(n log(n))|	O(n^2)
|Merge Sort|	Ω(n log(n))|	θ(n log(n))|	O(n log(n))
|Bucket Sort|	Ω(n+k)|	θ(n+k)|	O(n^2)
|Radix Sort|	Ω(nk)|	θ(nk)|	O(nk)
|Count Sort|	Ω(n+k)|	θ(n+k)|	O(n+k)

## Spring and Spring boot


## Java versions