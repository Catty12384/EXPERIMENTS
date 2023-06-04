AIM:
    
    To write a java program to insert elements into an array.
ALGORITHM:

		STEP-1 : Import Scanner class.
		STEP-2 : Create a class ArrayINS.
		STEP-3 : Declare all the variables required.
		STEP-4 : Get the values required from the user.
		STEP-5 : Get the inputs for the array.
		STEP-6 : Enter the position you wished to insert an element.
		STEP-7 : Enter the element to bbe inserted.
		STEP-8 : Print the array after insertion.
		
PROGRAM:

	 import java.util.Scanner;
	 public class ArrayINS 
	 {
    	public static void main(String [] args)
    	{
			Scanner s = new Scanner(System.in);
			System.out.print("Enter the number of elements:");
			int n =s.nextInt();
			int a[]=new int[n+1];
			System.out.print("Enter the elements:\n");
			for(int i=0;i<n;i++)
        	{
            	int m =s.nextInt();
            	a[i]=m;
        	}
			for(int i=0;i<n;i++)
			{
				System.out.print(a[i]);
			}
			System.out.print("\nEnter the position where you want to insert element:");
			int pos = s.nextInt();
			System.out.print("\nEnter the element you want to insert:");
			int x = s.nextInt();
			for(int i = (n-1); i >= (pos-1); i--)
			{
				a[i+1] = a[i];
			}
			a[pos-1] = x;
			for(int i=0;i<n;i++)
			{
				System.out.print(a[i]);
			}
			s.close();
	   }    
	}

	
OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/9c9a7141-5c33-43f1-8425-90d591b8880c)

CONCLUSION:

	The java program to insert elements into an array is written,compile,executed and the desired output is obtained successfully.
