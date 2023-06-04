# Assignment-2-LetsUpgrade
Assignment-2(31-05-2023)
**//Answers are written below the Problem Description**
Problem Description
---------------------------------------------------------------------------------------------------------------
Q1.Write a program to input an integer(A) from user and print the Ath month of the year.

Months list: {January, February, March, April, May, June, July, August, September, October, November, December}

Problem Constraints

1 <= A <= 12

Input Format
One line containing an integer integer A.

Output Format

One line containing the Ath month of the year.

Example Input

Input 1:
1
Input 2:

6

Example Output
Output 1:

January
Output 1:
June

Example Explanation

Explanation 1:

Clearly, January is the 1st month.
Explanation 2:



Clearly, June is the 6th month.

TEST CASES


Input:


1

Output:


January

Explanation: The input value is 1, which corresponds to the first month, January.

Test Case 2:

Input:
6

Output:


June

Explanation: The input value is 6, which corresponds to the sixth month, June.

Test Case 3:

Input:

12

Output:


December

Explanation: The input value is 12, which corresponds to the twelfth month, December.

Test Case 4:

Input:

3

Output:


March

Explanation: The input value is 3, which corresponds to the third month, March.

Test Case 5:

Input:

9

Output:


September

Explanation: The input value is 9, which corresponds to the ninth month, September.

Test Case 6:

Input:

5

Output:

May



---------------------------------------------------------------------------------------------------------------
Q2. Days In Month

Problem Description

You are given an integer A.

You have to tell how many days are there in the month denoted by Ain a non-leap year.

Months are denoted as follows:

January : 1
February : 2
March : 3
April : 4
May : 5
June : 6
July : 7
August : 8
September : 9
October : 10
November : 11
December : 12


Problem Constraints

1 <= A<= 12



Input Format

The input contains a single integer A.



Output Format

Print a single integer denoting the number of days on a single line.



Example Input
Input 1:

1
Input 2:

11


Example Output
Output 1:

31
Output 2:

30


Example Explanation
Explanation 1:

Number of days in January(1) in a non-leap year = 31.
Explanation 2:

Number of days in November(11) in a non-leap year = 30.


---------------------------------------------------------------------------------------------------------------
Problem Description
Q3.Write a program to input two numbers(A & B) from user and print the maximum element among A & B in each line.


Problem Constraints
1 <= A <= 1000000

1 <= B <= 1000000
Input Format

First line is a single integer A.Second line is a single integer B.
Output Format

One line containing the greater integer A or B.

Example Input
Input 1:

5
6
Input 2:
1000
10000


Example Output
Output 1:
6
Output 2:
10000


Example Explanation
Explanation 1:

Clearly, among 5 and 6, 6 is maximum.
Explanation 2:
Clearly, among 1000 and 10000, 10000 is ma


---------------------------------------------------------------------------------------------------------------
Problem Description
Q4.Write a program to input three numbers(A, B & C) from user and print the maximum element among A, B & C in each line.

Problem Constraints

1 <= A <= 1000000

1 <= B <= 1000000

1 <= C <= 1000000

Input Format
First line is a single integer A.Second line is a single integer B.Third line is a single integer C.
Output Format
One line containing an integer as per the question.

Example Input

Input 1:

5
6
7
Input 2:
1000
10000
100000

Example Output
Output 1:
7
Output 2:
100000

Example Explanation

Explanation 1:

Clearly, among 5, 6 and 7, 7 is maximum.
Explanation 2:
Clearly, among 1000, 10000 and 100000, 100000 is maximum.

TEST CASE

Edge Case 1:
Input:
```
1
1
1
```
Output:
```
1
```
Explanation: All three input values are the same (1). Therefore, the maximum element among them is also 1.

Edge Case 2:
Input:
```
1000000
1
1
```
Output:
```
1000000
```
Explanation: The first input value (1000000) is the largest among the three, so it is the maximum element.

Edge Case 3:
Input:
```
1
1000000
1
```
Output:
```
1000000
```
Explanation: The second input value (1000000) is the largest among the three, so it is the maximum element.

Edge Case 4:
Input:
```
1
1
1000000
```
Output:
```
1000000
```
Explanation: The third input value (1000000) is the largest among the three, so it is the maximum element.

Edge Case 5:
Input:
```
1000000
1000000
1000000
```
Output:
```
1000000
```
Explanation: All three input values are the same (1000000). Therefore, the maximum element among them is also 1000000.

Edge Case 6:
Input:
```
1
999999
1000000
```
Output:
```
1000000
```
Explanation: The third input value (1000000) is the largest among the three, so it is the maximum element.

---------------------------------------------------------------------------------------------------------------
Problem Description

Q5.Write a program to input an integer from user and print 1 if it is odd otherwise print 0.

Problem Constraints

1 <= N <= 1000000

Input Format
One line containing an integer N.


Output Format

Print either 1 or 0 as per the question.
Example Input

Input 1:

5
Input 2:

1000

Example Output

Output 1:

1
Output 2:
0
Example Explanation

Explanation 1:

Clearly, 5 is odd.
Explanation 2:

Clearly, 1000 is even.

---------------------------------------------------------------------------------------------------------------
Problem Description

Q6.Write a program to input two numbers(A & B) from user and print the minimum element among A & B in each line.

Problem Constraints

1 <= A <= 1000000

1 <= B <= 1000000


Input Format

First line is a single integer A.Second line is a single integer B.

Output Format

One line containing an integer as per the question.

Example Input

Input 1:

5
6
Input 2:
1000
10000
Example Output

Output 1:

5
Output 2:
1000

Example Explanation
Explanation 1:
Clearly, among 5 and 6, 5 is minimum.
Explanation 2:
Clearly, among 1000 and 10000, 1000 is minimum.


TEST CASE

Edge Case 1:
Input:
```
1
1
```
Output:
```
1
```
Explanation: Both input values are the same (1). Therefore, the minimum element among them is also 1.

Edge Case 2:
Input:
```
1000000
1
```
Output:
```
1
```
Explanation: The second input value (1) is smaller than the first input value (1000000). Therefore, it is the minimum element.

Edge Case 3:
Input:
```
1
1000000
```
Output:
```
1
```
Explanation: The first input value (1) is smaller than the second input value (1000000). Therefore, it is the minimum element.

Edge Case 4:
Input:
```
999999
1000000
```
Output:
```
999999
```
Explanation: The first input value (999999) is smaller than the second input value (1000000). Therefore, it is the minimum element.

Edge Case 5:
Input:
```
1000000
1000000
```
Output:
```
1000000
```
Explanation: Both input values are the same (1000000). Therefore, the minimum element among them is also 1000000.


---------------------------------------------------------------------------------------------------------------
Problem Description

Q7.Write a program to input three numbers(A, B & C) from user and print the minimum element among A, B & C.

Problem Constraints

1 <= A <= 1000000

1 <= B <= 1000000

1 <= C <= 1000000

Input Format

First line is a single integer A.Second line is a single integer B.Third line is a single integer C.

Output Format

One line containing an integer as per the question.

Example Input

Input 1:

5
6
7
Input 2:

1000
10000
100000

Example Output

Output 1:-
5

Output 2:-
1000

Example Explanation

Explanation 1:

Clearly, among 5, 6 and 7, 5 is minimum.
Explanation 2:
Clearly, among 1000, 10000 and 100000, 1000 is minimum.

TEST CASE

Edge Case 1:
Input:
```
1
1
1
```
Output:
```
1
```
Explanation: All three input values are the same (1). Therefore, the minimum element among them is also 1.

Edge Case 2:
Input:
```
1000000
1
1
```
Output:
```
1
```
Explanation: Both the second and third input values are smaller than the first input value (1000000). Therefore, the minimum element is 1.

Edge Case 3:
Input:
```
1
1000000
1
```
Output:
```
1
```
Explanation: Both the first and third input values are smaller than the second input value (1000000). Therefore, the minimum element is 1.

Edge Case 4:
Input:
```
1
1
1000000
```
Output:
```
1
```
Explanation: Both the first and second input values are smaller than the third input value (1000000). Therefore, the minimum element is 1.

Edge Case 5:
Input:
```
1000000
1000000
1000000
```
Output:
```
1000000
```
Explanation: All three input values are the same (1000000). Therefore, the minimum element among them is also 1000000.

Edge Case 6:
Input:
```
1
999999
1000000
```
Output:
```
1
```
Explanation: The first input value (1) is smaller than the second and third input values. Therefore, it is the minimum element.


---------------------------------------------------------------------------------------------------------------
Problem Description

Q8.You are given 3 integer angles(in degrees) A, B and C of a triangle. You have to tell whether the triangle is valid or not.

A triangle is valid if sum of its angles equals to 180.


Problem Constraints

1 <= A, B, C <= 180

Input Format

First line of the input contains an integer A.

Second line of the input contains an integer B.

Third line of the input contains an integer C.


Output Format


Print 1 if the triangle having given sides is valid, else print 0.



Example Input

Input 1:

60
60
60
Input 2:

30
40
50


Example Output

Output 1:

1
Output 2:

0

Example Explanation

Explanation 1:

Sum of angles = A + B + C = 60 + 60 + 60 = 180
Hence, the given triangle is valid.
Explanation 2:

Sum of angles = A + B + C = 30 + 40 + 50 = 120
As sum of angles is not equal to 180, the given triangle is not valid.

TEST CASE

Certainly! Here are some edge cases you can use to test your program:

Edge Case 1:
Input:
```
60
60
60
```
Output:
```
1
```
Explanation: All three angles are 60 degrees each, and their sum is 180 degrees. Therefore, the triangle is valid.

Edge Case 2:
Input:
```
90
45
45
```
Output:
```
1
```
Explanation: The angles are 90, 45, and 45 degrees, and their sum is 180 degrees. Therefore, the triangle is valid.

Edge Case 3:
Input:
```
45
45
90
```
Output:
```
1
```
Explanation: The angles are 45, 45, and 90 degrees, and their sum is 180 degrees. Therefore, the triangle is valid.

Edge Case 4:
Input:
```
1
89
90
```
Output:
```
0
```
Explanation: The angles are 1, 89, and 90 degrees, and their sum is not equal to 180 degrees. Therefore, the triangle is not valid.

Edge Case 5:
Input:
```
180
0
0
```
Output:
```
0
```
Explanation: The angles are 180, 0, and 0 degrees, and their sum is not equal to 180 degrees. Therefore, the triangle is not valid.

Edge Case 6:
Input:
```
120
60
1
```
Output:
```
0
```
Explanation: The angles are 120, 60, and 1 degree, and their sum is not equal to 180 degrees. Therefore, the triangle is not valid.

---------------------------------------------------------------------------------------------------------------
Problem Description
Q9.Write a program to input from user three numbers(A, B & C) representing side lengths of a triangle.

You have to print if the traingle is "equilateral", "scalene" or "isosceles".

Problem Constraints

1 <= A <= 100000

1 <= B <= 100000

1 <= C <= 100000

Input Format

One line containing three space separated integers A, B & C.

Output Format

One string either "equilateral", "scalene" or "isosceles".

Example Input

Input 1:

5 6 7
Input 2:

30 30 30


Example Output
Output 1:
scalene
Output 2:
equilateral

Example Explanation

Explanation 1:

Since all sides are different, hence it's a scalene triangle.
Explanation 2:

Since all sides are same, hence it's a equilateral triangle.

TEST CASE

Edge Case 1:
Input:
```
3 3 3
```
Output:
```
equilateral
```
Explanation: All three sides are of equal length, so the triangle is equilateral.

Edge Case 2:
Input:
```
5 4 6
```
Output:
```
scalene
```
Explanation: All three sides have different lengths, so the triangle is scalene.

Edge Case 3:
Input:
```
7 7 5
```
Output:
```
isosceles
```
Explanation: Two sides (7 and 7) are of equal length, so the triangle is isosceles.

Edge Case 4:
Input:
```
1 2 3
```
Output:
```
Invalid triangle
```
Explanation: The sum of the lengths of the two shorter sides (1 and 2) is not greater than the length of the longest side (3). Hence, this cannot form a valid triangle.

Edge Case 5:
Input:
```
0 0 0
```
Output:
```
Invalid triangle
```
Explanation: All side lengths are zero, which is not a valid triangle.

Edge Case 6:
Input:
```
100000 100000 100000
```
Output:
```
equilateral
```
Explanation: All three sides are of equal length (maximum allowed value), so the triangle is equilateral.

---------------------------------------------------------------------------------------------------------------
Q10.Problem Description

Take an integer A as input. You have to tell whether A is divible by both 5 and 11 or not.


Problem Constraints


1 <= A <= 109

Input Format


The input contains a single integer A.

Output Format


Print 1 if A is divisible by both 5 and 11, else print 0.

Example Input

Input 1:

55
Input 2:

22

Example Output

Output 1:


1
Output 2:

0


Example Explanation

Explanation 1:


55 is divisible by both 5 (5 * 11 = 55) and 11 (11 * 5 = 55).
Explanation 2:

22 is divisble by 11 (11 * 2 = 22),but it is not divisible by 5.

TEST CASE

Edge Case 1:
Input:
```
55
```
Output:
```
1
```
Explanation: 55 is divisible by both 5 and 11, so the output is 1.

Edge Case 2:
Input:
```
10
```
Output:
```
0
```
Explanation: 10 is divisible by 5 but not by 11, so the output is 0.

Edge Case 3:
Input:
```
11
```
Output:
```
0
```
Explanation: 11 is divisible by 11 but not by 5, so the output is 0.

Edge Case 4:
Input:
```
50
```
Output:
```
0
```
Explanation: 50 is divisible by 5 but not by 11, so the output is 0.

Edge Case 5:
Input:
```
0
```
Output:
```
1
```
Explanation: 0 is divisible by both 5 and 11, so the output is 1.

Edge Case 6:
Input:
```
110
```
Output:
```
1
```
Explanation: 110 is divisible by both 5 and 11, so the output is 1.
---------------------------------------------------------------------------------------------------------------
Problem Description

Q11.You are given a Bank account having N amount and you are asked to perform ADD(credit) or SUBTRACT(debit) operation of an amount X.]

After the operation print the amount left in the Bank account. If the debit amount is greater than current balance print "Insufficient Funds"(without quotes) and the operation is skipped.

Problem Constraints

1 <= N, X <= 105

Input Format

First line contains a single integer N denoting the balance in bank account.

Next line contains two space separated integers Type and Amount(X).

If Type == 1, Perform ADD operation.
If Type == 2, Perform SUBTRACT operation.


Output Format

Print Amount in the bank balance after the operation.

Example Input

Example Input 1 :
1000
1 500

Example Input 2 :
1000
2 200

Example Input 3 :
1000
2 1500
Example Output

Example Output 1 :
1500

Example Output 2 :
800

Example Output 3 :
Insufficient Funds
Example Explanation

Example 1 :
Initially bank balance is 1000.
ADD 500, bank balance becomes 1500, print it.

Example 2 :
Initially bank balance is 1000.
SUBTRACT 200, bank balance becomes 800, print it.

Example 3 :
Initially bank balance is 1000.
SUBTRACT 1500, can't subtract since balance is only 1000, print "Insufficient Finds".
---------------------------------------------------------------------------------------------------------------
Q1 ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class Month{
    public static void main(String[] args){
        int A;
        String month ="";
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        switch(A){
            case 1:
                month = "January";
                break;
            case 2:
                month = "February";
                break;
            case 3:
                month = "March";
                break;
            case 4:
                month = "April";
                break;
            case 5:
                month = "May";
                break;
            case 6:
                month = "June";
                break;
            case 7:
                month = "July";
                break;
            case 8:
                month = "August";
                break;
            case 9:
                month = "September";
                break;
            case 10:
                month = "October";
                break;
            case 11:
                month = "November";
                break;
            case 12:
                month = "December";
                break;
            default:
                System.out.println("Invalid Input");
                month = "Not Exist";
                break;
        }
        System.out.println(+A+ " month is " +month);
    }
}
---------------------------------------------------------------------------------------------------------------
Q2.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class NoOfDaysInAMonth{
    public static void main(String[] args){
        int a;
        int days = 0;
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();
        switch(a){
            case 1:
                days = 31;
                break;
            case 2:
                days = 28;
                break;
            case 3:
                days = 31;
                break;
            case 4:
                days = 30;
                break;
            case 5:
                days = 31;
                break;
            case 6:
                days = 30;
                break;
            case 7:
                days = 31;
                break;
            case 8:
                days = 31;
                break;
            case 9:
                days = 30;
                break;
            case 10:
                days = 31;
                break;
            case 11:
                days = 30;
                break;
            case 12:
                days = 31;
                break;
            default:
                System.out.println("Invalid Input");
                break;
        }
        System.out.println(" no of days in " +a+ " month is:" +days);
    }
}
---------------------------------------------------------------------------------------------------------------
Q3.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class GreatestOfTwoNumbers {
    public static void main(String[] args){
        int A,B = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        B = sc.nextInt();
        if(A>B){
            System.out.println(+A);
        }
        else if(B>A){
            System.out.println(+B);
        }
        else if(A==B){
            System.out.println(+A+ " and " +B+ " Are equal");
        }
        else{
            System.out.println("Invalid Input");
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q4.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class GreatestAmongThreeNum {
    public static void main(String[] args){
        int A,B,C = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        B = sc.nextInt();
        C = sc.nextInt();
        if(A>B && A>C){
            System.out.println(+A);
        }
        else if(B>A && B>C){
            System.out.println(+B);
        }
        else{
            System.out.println(+C);
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q5.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class OddNum {
    public static void main(String[] args) {
        int N = 0;
        Scanner sc = new Scanner(System.in);
        N = sc.nextInt();
        if (N % 2 != 0) {
            System.out.println(1);
        } else {
            System.out.println(0);
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q6.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class MinimumNumAmongTwoNum {
    public static void main(String[] args) {
        int A, B = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        B = sc.nextInt();
        if (A > B) {
            System.out.println(B);
        }
        else{
            System.out.println(A);
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q7.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class MinimumNumAmongThreeNum {
    public static void main(String[] args) {
        int A,B,C = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        B = sc.nextInt();
        C = sc.nextInt();
        if (A > B && C > B) {
            System.out.println(B);
        }
        else if(A > C && B > C){
            System.out.println(C);
        }
        else{
            System.out.println(A);
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q8.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class Triangle {
    public static void main(String[] args) {
        int A,B,C = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        B = sc.nextInt();
        C = sc.nextInt();
        if (A+B+C==180) {
            System.out.println(1);
        }
        else{
            System.out.println(0);
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q9.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class TriangleTypes {
    public static void main(String[] args) {
        int A,B,C = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        B = sc.nextInt();
        C = sc.nextInt();
        if (A==B&&A==C) {
            System.out.println("equilateral");
        }
        else if(A!=B && A!=C){
            System.out.println("scalene");
        }
        else{
            System.out.println("isosceles");
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q10.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class DivisibleByFiveAndEleven {
    public static void main(String[] args) {
        int A = 0;
        Scanner sc = new Scanner(System.in);
        A = sc.nextInt();
        if (A % 5 == 0 && A % 11 == 0) {
            System.out.println(1);
        } else {
            System.out.println(0);
        }
    }
}

---------------------------------------------------------------------------------------------------------------
Q11.ANS:
package com.dsa.jagadeesh;

import java.util.Scanner;

public class BankAmount {
    public static void credit(int N, int amount){
        N = N + amount;
        System.out.println(N);
    }
    public static void Debit(int N, int amount){
        if (N >= amount) {
            N = N - amount;
            System.out.println(N);
        }
        else {
            System.out.println("Insufficient Funds");
        }
    }
    public static void main(String[] args) {
        int N = 0;
        int task, amount = 0;
        Scanner sc = new Scanner(System.in);
        N = sc.nextInt();
        task = sc.nextInt();
        amount = sc.nextInt();
        if (task == 1) {
            BankAmount.credit(N,amount);
        }
        else{
            BankAmount.Debit(N,amount);
        }

    }

}
---------------------------------------------------------------------------------------------------------------
SUBMITTED BY:
JAGADEESH GUNTI
-------------------------------------------------**THANK YOU**-------------------------------------------------
