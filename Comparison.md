AIM:

    To write a Java program to compare two numbers.
        
PROCEDURE:

    STEP-1: Import the Java Scanner to get input from the user.
    STEP-2: Declare teh variables that we are about to use.
    STEP-3: Instantiate the Scanner class.
    STEP-4: Get two numbers as input from the user.
    STEP-5: Compare both the numbers using ladder if statement and print the output.
    STEP-6: Close the object of the Scanner class.
        
PROGRAM:

import java.util.Scanner;

public class Comparison

{

    public static void main(String args[])
    {
        int a,b;
        Scanner s=new Scanner (System.in);
        System.out.print("Enter a number: ");
        a=s.nextInt();
        System.out.print("Enter a number: ");
        b=s.nextInt();
        if(a==b)
        {
            System.out.println("Numbers are the same.");
        }
        else if(a>b)
        {
            System.out.println(a+" is greater than "+b);
        }
        else
        {
            System.out.println(b+" is greater than "+a);
        }
        s.close();
    };
}

OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/e10ce8c4-37f5-4c0f-aa5c-a6cf5298409e)

RESULT:

    The Java program to compare two numbers is written,compile,executed and the desired output is obtained succes
