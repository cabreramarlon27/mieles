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
* **What is the difference between Comparable and Comparator?**
    * Need to dig more
*
## Threads

## Completable futures

## Performance

### Garbage Collectors
* **What does System.gc and Runtime.gc methods do?**
    * These methods can be used as a hint to the JVM, in order to start a garbage collection. However, this it is up to the Java Virtual Machine (JVM) to start the garbage collection immediately or later in time.
* **If an object reference is set to null, will the Garbage Collector immediately free the memory held by that object?**
    * No, the object will be available for garbage collection in the next cycle of the garbage collector.
* **When does an Object becomes eligible for Garbage collection in Java?**
    * A Java object is subject to garbage collection when it becomes unreachable to the program in which it is currently used.

### Java memory management
**Future lectures**
* [Sun HotSpot VM](https://javaeesupportpatterns.blogspot.com/2011/08/java-heap-space-hotspot-vm.html)
* [IBM VM](https://javaeesupportpatterns.blogspot.com/2012/02/java-heap-space-ibm-vm.html)
* [Oracle JRockit VM](https://javaeesupportpatterns.blogspot.com/2012/02/java-heap-space-jrockit-vm.html)
* [Oracle - Java memory management white paper](http://java.sun.com/j2se/reference/whitepapers/memorymanagement_whitepaper.pdf)

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



## Java versions

## Complexity

## Exception Handling
* **What is the difference between Exception and Error in java?**
    * Exception and Error classes are both subclasses of the Throwable class. The Exception class is used for exceptional conditions that a user’s program should catch. The Error class defines exceptions that are not expected to be caught by the user program.