AIM:

	To write a Java program to print even numbers.

PROCEDURE:

	STEP-1: Import the Java Scanner to get input from the user.
	STEP-2: Declare the variables that we are about to use.
	STEP-3: Instantiate the Scanner class.
	STEP-4: In a for loop initialize i=0 and give the condition to be i<=20 and increament the value.
	STEP-5: Using a system.out.print statement print the output
	STEP-6: Close the object of the Scanner class.

PROGRAM:

	public class EvenNumbers
	{
    	public static void main(String args[])
    	{
        	int i;
        	System.out.println("Even Numbers: ");
        	for(i=0;i<=20;i++)
        	{
            	if(i%2==0)
            	{
                	System.out.print(i+"  ");
            	}
        	}
    	}
	}

OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/de0e3746-6482-4d91-ab85-4af2f45f779c)

RESULT:

	The Java program to print even numbers is written,compile,executed and the desired output is obtained successfully.
