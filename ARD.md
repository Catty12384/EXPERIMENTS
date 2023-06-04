AIM:
	
	To write a java program to add, retrieve and remove the element from the ArrayList.
	
ALGORITHM:

	STEP-1 : Import  java Util package.
	STEP-2 : Create an onject for two ArrayList.
	STEP-3 : Add the elements for both the ArrayLists.
	STEP-4 : Print the ArrayLists.
	STEP-5 : Delete a element from the ArrayList.
	STEP-6 : Retrive an element from the ArrayList.
	
PROGRAM:
		
	import java.util.*;
	class ArrayINS
	{
		public static void main(String[] args)
		{
			ArrayList<String> al = new ArrayList<String>();
			System.out.println("Size of ArrayList: "+al.size());
			//Adding the elements
			al.add("Java");
			al.add("JDBC");
			System.out.println("Elements of first ArrayList: "+al);
			ArrayList<String> al2 = new ArrayList<String>();
			al2.add("EJB");
			al2.add("Struts");
			//Adding the both array
			al2.addAll(al);
			System.out.println("Elements of second ArrayList: "+al2);
			//remove the element
			al2.remove("EJB");
			System.out.println("Elements of ArrayList after deletion: "+al2);
			System.out.println("Size of ArrayList: "+al2.size());
			//Retriving 2nd index element
			System.out.println("The element at 2nd index is: "+al2.get(2));
		}
	}
OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/3c68ca6c-d469-4205-987d-4c0d36839989)

CONCLUSION:
	
	The java program to add, retrieve and remove the element from the ArrayList is written,compile,executed and the desired output is obtained successfully.
