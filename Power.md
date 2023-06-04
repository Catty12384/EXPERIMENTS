AIM:

    To define a java method to calculate power of a number raised to other.
ALGORITHM:
    	
		STEP-1 : Import the Scanner class.
		STEP-2 : Create a class Power to calculate the power of  the number.
		STEP-3 : Create a main function.
		STEP-4 : Create a variable for Scanner class.
		STEP-5 : Declare the variables.
		STEP-6 : Get values from the user.
		STEP-7 : Call the function to print the power.
PROGRAM:

	import java.util.Scanner;
	public class Power 
	{
    	public static int power(int a, int b)
    	{
            if(b==0)
        	{
            	return 1;
        	}
        	else
        	{
            	return(a*power(a,b-1));
			}
    	}
   	 	public static void main(String args[])
    	{
        	Scanner s = new Scanner (System.in);
        	int a,b;
        	System.out.print("Enter the number: ");
        	a=s.nextInt();
        	System.out.print("Enter the power: ");
        	b=s.nextInt();
        	System.out.println(power(a,b));
        	s.close();
    	}
	}

OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/4927f226-d269-4ad1-ad70-de26f66c45cd)

CONCLUSION:

	The Java program to calculate power of a number raised to other is written,compile,executed and the desired output is obtained successfully.

