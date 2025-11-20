## EX3 Write a program to count the number of digits in an integer.
## DATE:13/08/2025
## AIM:
To write a java program to count the number of digits in an integer.

## Algorithm
Start and read an integer n from the user.
Initialize a variable count = 0.
If n == 0, set count = 1 (since 0 has 1 digit).
Otherwise, repeat while n ≠ 0:   • Divide n by 10   • Increment count
Display "Number of digits: " + count and stop.
## Program:
```
Program to to count the number of digits in an integer
Developed by: MOPURI ANKITHA
RegisterNumber: 212223040117

import java.util.Scanner;

public class CountDigits {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n=sc.nextInt();
        int count=0;
        if(n==0){
            count=1;
        }
        else{
             while(n!=0){
                 n=n/10;
                 count++;
             }
        }
        System.out.println("Number of digits: " + count);
    }
}
 
```
## Output:
<img width="1032" height="379" alt="image" src="https://github.com/user-attachments/assets/5cf9ceac-ae22-47b5-9470-a15f85104695" />

## Result:
Thus, the Java program to to count the number of digits in an integer is implemented successfully.
