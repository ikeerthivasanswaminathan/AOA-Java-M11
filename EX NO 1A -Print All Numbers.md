# EX 1A Print All Numbers 

## DATE: 16/07/2026

## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm

1. Start the program and import the `Scanner` class to take user input.

2. Create a `Scanner` object to read an integer input `N` from the user.

3. Check if `N` is greater than 0; if not, display `"Invalid input. N must be greater than 0."`

4. Use a `for` loop to iterate from 1 to `N`.

5. Print each number separated by a space on the same line.
   
## Program:

Program to implement Reverse a String

Developed by: KEERTHIVASAN S

Register Number: 212223220046

```
import java.util.Scanner;
public class PrintNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int N = scanner.nextInt();
        if (N <= 0) {
            System.out.println("Invalid input. N must be greater than 0.");
        } else {
            for (int i = 1; i <= N; i++) {
                System.out.print(i + " ");
            }
        }
        scanner.close();
    }
}

*/
```

## Output:

<img width="491" height="159" alt="m11-t1op" src="https://github.com/user-attachments/assets/13c9605f-fe53-4887-ba2f-36764135f998" />

## Result:
Thus, the program successfully print all the numbers from 1 to N.
