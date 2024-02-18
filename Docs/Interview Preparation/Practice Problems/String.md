## String

1.How to reverse a string in Java.

```Java
import java.util.Scanner;

public class Main  {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        String word = input.nextLine();
        String RevWord = "";
        for (int i = word.length()-1;i>=0 ; i--) {
            RevWord += word.charAt(i);
        }
        System.out.println(RevWord);
    }
}
```

2.Write a Java program to check if two strings are anagram?

```java

```
