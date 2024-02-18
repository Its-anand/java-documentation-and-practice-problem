# String Methods

1. **`length`**:
    - Returns the **number of elements** in the array.
    - Example:
        ```java
        String[] arr = { "Apple", "Banana", "Orange" };
        int len = arr.length; // len will be 3
        ```

2. **`equals(Object other)`**:
    - Compares the content of two arrays for equality.
    - Example:
        ```java
        String[] arr1 = { "Apple", "Banana", "Orange" };
        String[] arr2 = { "Apple", "Banana", "Orange" };
        boolean isEqual = arr1.equals(arr2); // true
        ```

3. **`clone()`**:
    - Creates a **shallow copy** of the array.
    - Example:
        ```java
        String[] original = { "Apple", "Banana", "Orange" };
        String[] copy = original.clone();
        ```

4. **`toString()`**:
    - Converts the array to a **string representation**.
    - Example:
        ```java
        String[] arr = { "Apple", "Banana", "Orange" };
        String arrString = Arrays.toString(arr); // "[Apple, Banana, Orange]"
        ```

5. **`sort()`**:
    - Sorts the array **lexicographically** (alphabetically).
    - Example:
        ```java
        String[] arr = { "Banana", "Apple", "Orange" };
        Arrays.sort(arr); // arr will be ["Apple", "Banana", "Orange"]
        ```

6. **`binarySearch(Object[] a, Object key)`**:
    - Searches for the specified element using **binary search**.
    - Requires the array to be sorted.
    - Example:
        ```java
        String[] arr = { "Apple", "Banana", "Orange" };
        int index = Arrays.binarySearch(arr, "Banana"); // 1
        ```


7. **`copyOf(String[] original, int newLength)`**:
   - Creates a new array with the specified **length** and copies elements from the original array.
   - Example:
       ```java
       String[] original = { "Apple", "Banana", "Orange" };
       String[] shorterCopy = Arrays.copyOf(original, 2); // ["Apple", "Banana"]
       ```

8. **`fill(String[] a, String val)`**:
   - Fills the entire array with the specified **value**.
   - Example:
       ```java
       String[] arr = new String[3];
       Arrays.fill(arr, "Fruit"); // ["Fruit", "Fruit", "Fruit"]
       ```

9. **`hashCode()`**:
   - Returns the **hash code** for the array.
   - Example:
       ```java
       String[] arr = { "Apple", "Banana", "Orange" };
       int hash = arr.hashCode();
       ```

10. **`isEmpty()`**:
    - Checks if the array is **empty** (contains no elements).
    - Example:
        ```java
        String[] emptyArr = {};
        boolean isEmpty = emptyArr.isEmpty(); // true
        ```

11. **`contains(String key)`**:
    - Checks if the array contains the specified **element**.
    - Example:
           ```java
           String[] arr = { "Apple", "Banana", "Orange" };
           boolean containsBanana = Arrays.asList(arr).contains("Banana"); // true
           ```

