AIM:

    To write a Java program to perform arithmetic operations.
        
PROCEDURE:

    STEP-1: Import the Java Scanner to get input from the user.
    STEP-2: Declare teh variables that we are about to use.
    STEP-3: Instantiate the Scanner class.
    STEP-4: Get two numbers as input from the user.
    STEP-5: Perform all arithmetic operations such as Addition,Difference,Product,Quotient and Modulus and print the output.
    STEP-6: Close the object of the Scanner class.
        
PROGRAM:

import java.util.Scanner;

public class ArithmeticOperations
{

    public static void main(String args[])
    {
        int a,b;
        Scanner s=new Scanner(System.in);
        System.out.print("Enter a number:");
        a=s.nextInt();
        System.out.print("Enter a number:");
        b=s.nextInt();
        System.out.println("Sum: "+(a+b));
        System.out.println("Difference: "+(a-b));
        System.out.println("Product: "+(a*b));
        System.out.println("Quotient: "+(a/b));
        System.out.println("Remainder: "+(a%b));
        s.close();
    };
}

OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/d1dad2e5-7d38-400f-a0c7-d1f804678ca6)

RESULT:

    The Java program to perform arithmetic operations is written,compile,executed and the desired output is obtained succes
