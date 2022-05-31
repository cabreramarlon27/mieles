# Data structures [Read More](https://hackernoon.com/50-data-structure-and-algorithms-interview-questions-for-programmers-b4b1ac61f5b0)

## General considerations for Java collections
* Choosing the right type of the collection to use, based on the application’s needs, is very crucial for its performance. For example if the size of the elements is fixed and know a priori, we shall use an Array, instead of an ArrayList.
* Some collection classes allow us to specify their initial capacity. Thus, if we have an estimation on the number of elements that will be stored, we can use it to avoid rehashing or resizing.
* Always use Generics for type-safety, readability, and robustness. Also, by using Generics you avoid the ClassCastException during runtime.
* Use immutable classes provided by the Java Development Kit (JDK) as a key in a Map, in order to avoid the implementation of the hashCode and equals methods for our custom class.
* Program in terms of interface not implementation.
* Return zero-length collections or arrays as opposed to returning a null in case the underlying collection is actually empty.

## List
* **Which list implementations is faster?**
    * LinkedList, implementations that use arrays are slower the the shifted and the last position added.
* **What differences exist between Iterator and ListIterator?**
    * An Iterator can be used to traverse the Set and List collections, while the ListIterator can be used to iterate only over Lists.
    * The Iterator can traverse a collection only in the forward direction, while the ListIterator can traverse a List in both directions.
    * The ListIterator implements the Iterator interface and contains extra functionality, such as adding an element, replacing an element, getting the index position for previous and next elements, etc.

## Maps
* **What is the difference between HashMap and Hashtable?**
    * HashMap allows null keys and values
    * Hastable is syncronized and HashMap not. HashMap is preferred for single threaded environments
    * HashMap can be iterated over its set of keys and is fail-fast
    * Hashtable is considered legacy class

## Queue
* **What is a priority Queue?**
    * Is and unbounded queue based on a priority heap and their elements are ordered.

## Set
* **What is the difference between HashSet and TreeSet?**
    * TreeSet elements are sorted, but takes more time(O(Log n )) for regular operations like add remove or contain. It use a Red-Black tree algorithm to sort elements
    * HashSet allows null object TreeSet don't because it uses compareTo method to compare keys
    *

## Arrays
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

