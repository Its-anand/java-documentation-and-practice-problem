# Array

**1. In java, arrays data is not stored sequentially? like in c cpp where if int array starting address is 1000 then the next index array will be 1004.**

Ans: In Java, data is not stored sequentially in memory like in C or C++. This is because Java arrays are not raw values, but references to objects on the heap. The objects themselves may be scattered in different memory locations, depending on how the JVM allocates and manages them. Therefore, you cannot assume that the next index of an array will be at a fixed offset from the previous one.

