# Fibonacci-Sequence
A program that calculates F(n) by the given value of n
import java.util.Scanner;
public class fibonacciSeq {
    public static void main(String[] args) {

        System.out.println("Please enter the index number of Fibonacci Sequence");

        Scanner userInput = new Scanner(System.in);
        int N = userInput.nextInt();

        System.out.println("The number you have entered is : " + N);

        int num1 = 0, num2 = 1;
        for (int i = 0; i < N; i++) {
            System.out.print(num1 + "  ");

            int sum = num1 + num2;

            num1 = num2;
            num2 = sum;


        }
        System.out.println("\nThe value of index number " + N + " is " + num1);

    }
    ```
