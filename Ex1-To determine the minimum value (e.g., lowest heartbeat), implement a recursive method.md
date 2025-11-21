## EX3 Write a program to count the number of digits in an integer.
## DATE: 13/08/2025
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program.
2. Read an integer input num from the user.
3. If num is equal to 0, then the number has 1 digit.
4. Convert num to its absolute value to handle negative numbers.
5. Initialize a counter variable count = 0.
6. Repeat the following steps while num > 0:
Divide num by 10 (integer division).
Increment count by 1.
7. After the loop ends, count will contain the number of digits.
8.  Display the value of count.
9. End the program.
## Program:

Program to to count the number of digits in an integer

```
import java.util.Scanner;

public class CountDigits {

    public static int countDigits(int num) {
        int count = 0;
        if (num == 0) return 1; 
        num = Math.abs(num);   
        while (num > 0) {
            count++;
            num /= 10;
        }
        return count;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();

        int digits = countDigits(num);
        System.out.println("Number of digits: " + digits);
    }
}
```
## Output:
<img width="795" height="349" alt="image" src="https://github.com/user-attachments/assets/0c1ccd19-8c68-449a-b09a-2b65848028f6" />
## Result:
Thus, the Java program to to count the number of digits in an integer is implemented successfully.
