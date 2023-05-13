AIM:
	
	To write a Java program to find the number of days in a month.

PROCEDURE:
	
	STEP-1: Import the Java Scanner to get input from the user.
	STEP-2: Declare teh variables that we are about to use.
	STEP-3: Instantiate the Scanner class.
	STEP-4: Get two numbers as input from the user.
	STEP-5: Calculate the number of months and print the output.
	STEP-6: Close the object of the Scanner class.
PROGRAM:

	import java.util.*;

	public class DaysInAMonth

	{

    public static void main(String args[])
    {
        String a;
        Scanner s= new Scanner(System.in);
        System.out.print("Enter the month: ");
        a=s.nextLine();
        System.out.print("Enter the year: ");
        int y=s.nextInt();
        if(a.equals("January")||a.equals("March")||a.equals("May")||a.equals("July")||a.equals("August")||a.equals("October")||a.equals("December"))
        {
            System.out.println(a+" has 31 days");
        }
        else if(a.equals("February")&&(y%4==0))
        {
            System.out.println("February has 29 days");
        }
        else if(a.equals("February"))
        {
            System.out.println("February has 28 days");
        }
        else
        {
            System.out.println(a+" has 30 days");
        }
        s.close();
    };
}

OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/ca28039e-a31b-4d7e-9847-9f0984cc0cc2)

RESULT:

	The Java program to find the number of days in a month is written,compile,executed and the desired output is obtained successfully.
