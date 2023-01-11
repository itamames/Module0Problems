# Module0Problems


These are problems to refresh your Java knowledge and prepare for the class. These are not graded and the solutions will be provided soon. 

Give them your best shot without outright googling the solution, remember you are cheating yourself of knowledge if you take shorcuts.

## Problem 1 Loops

Create a program that calculates the sum of all numbers up to the input.

```java
import java.util.Scanner;
public class CalculateSum
{

    public static void main(String args[])
    {
        //todo

    }
    
}
```

## Problem 2 Conditional Statements

Generate 5 random numbers between 1 and 100 using either the rand() or randi() functions. 
For each number genereated:
* A) If the value is less than 10 have the script display the number as is.
* B) If the value is greater than 50 have the script display the number plus 100.
* C) If the value meets neither (A) or (B)'s conditions then display the number minus 100.

```java
import java.util.Random;

public class ConitionalIf {
    public static void main(String args[]) {
        Random rand = new Random();
        int newRand = 0;
        ///todo
    }
}
```

## Problem 3 Recursion

Create a program that solves the Tower of Hanoi game, ie, moves all disks fron A to C, one at a time.
![Tower of Hanoi](https://cdn-media-1.freecodecamp.org/images/0*UB4f9VNg1RRs4k93.png)


```java
class TowerOfHanoi 
{
    static void towerOfHanoi(int n, char from_rod,
                             char to_rod, char aux_rod)
    {
       // your code here
    }
 
    // Driver code
    public static void main(String args[])
    {
        int N = 3;
 
        // A, B and C are names of rods
        towerOfHanoi(N, 'A', 'C', 'B');
    }
}
```
## Problem 4 Double Loops

Find a pair with the given sum in an array.

```text
Input:
 
nums = [8, 7, 2, 5, 3, 1]
target = 10
 
Output:
 
Pair found (8, 2)
or
Pair found (7, 3)
 
 
Input:
 
nums = [5, 2, 6, 8, 1, 9]
target = 12
 
Output: Pair not found
```

Solution:
```java
class Main
{
    // Naive method to find a pair in an array with a given sum
    public static void findPair(int[] nums, int target)
    {
       
       //todo
 
        // we reach here if the pair is not found
        System.out.println("Pair not found");
    }
 
    public static void main (String[] args)
    {
        int[] nums = { 8, 7, 2, 5, 3, 1 };
        int target = 10;
 
        findPair(nums, target);
    }
}
```

## Problem 5 Double Loops + Conditional

Given an integer array, find the maximum product of two integers in it.

```text

A ={-10, -2, 5, 6, -2}

```

Solution
```java
class Main
{
    // A naive solution to finding the maximum product of two integers
    // in an array
    public static void findMaximumProduct(int[] A)
    {
        //todo
 
        System.out.print("Pair is (" + A[max_i] + ", " + A[max_j] + ")");
    }
 
    public static void main (String[] args)
    {
        int[] A = { -10, -3, 5, 6, -2 };
 
        findMaximumProduct(A);
    }
}
```

## Problem 6 Strings

Given a string, check if it is a rotated palindrome or not.

For example,

CBAABCD is a rotated palindrome as it is a rotation of palindrome ABCDCBA.
BAABCC is a rotated palindrome as it is a rotation of palindrome ABCCBA.

```java
class Main
{
    // Recursive function to check if `str[low…high]` is a palindrome or not
    public static boolean isPalindrome(String str, int low, int high)
    {
       //todo
    }
 
    // Function to check if a given string is a rotated palindrome or not
    public static boolean isRotatedPalindrome(String str)
    {
        // base case
        if (str == null) {
            return false;
        }
 
       //todo
 
        // return false if no rotation is a palindrome
        return false;
    }
 
    public static void main(String[] args)
    {
        // palindromic string
        String str = "ABCDCBA";
 
        //todo
    }
}
```
