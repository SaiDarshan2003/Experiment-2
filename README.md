# Experiment-1

# Compare Numbers

## Aim:
  To write a Java program to perform comparisons on the given numbers.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it CompareNumbers.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using comparing operators.

Step 5 : Display the operations done the input numbers in the terminal.

## Program
```
import java.util.Scanner;
public class CompareNumbers
{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter first number");
        int x = sc.nextInt();
        System.out.println("Enter second number");
        int y = sc.nextInt();
        System.out.println("By comparing two numbers largest number :");
        if (x > y) {
            System.out.println(x);
        } else {
            System.out.println(y);
        }
        System.out.println("By comparing two numbers smallest number :");
        if (x > y) {
            System.out.println(y);
        } else {
            System.out.println(x);
        }
        System.out.println("By comparing two numbers are equal or not :");
        if (x == y) {
            System.out.println("Equal");
        } else {
            System.out.println("Not equal");
        }
    }
}
```

## Output
![2](https://github.com/SaiDarshan2003/Experiment-2/assets/94692595/1db2e929-f544-4baa-9663-9134a0e9de83)


## Result 
  We have successfully created a Java program to display the comparisons on input numbers.
