# Day-1-with-java

Hello Everyone. Today is my Day1 with java. I am starting learning java.Here is my first program what i learned and practiced today.

Question: write a program to find whether the given number is even or odd in java?

Ans: 

import java.util.Scanner;

public class Day1 {

    public static void main(String[] args) {
    
        Scanner Scan = new Scanner(System.in);

        int num = Scan.nextInt();

        if(num % 2 == 0)
            System.out.println("even");
        else
            System.out.println("odd");
    }
}
