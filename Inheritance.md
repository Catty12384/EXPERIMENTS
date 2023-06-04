AIM:
	
	To write a java program to explain inheritance.
	
ALGORITHM:

	STEP-1 : Create a class named Animal having a function.
	STEP-2 : Create a another class named Bird which extends the Animal class.
	STEP-3 : Create a main class.
	STEP-4 : Create an object for the class named bird.
	STEP-5 : Using the object call the functions of other classes.
	
PROGRAM:
	
	
	public class Animal
	{
		void walk()
		{
			System.out.println("I am walking");
		}
	}
    
    

	class Bird extends Animal 
	{
		void fly() 
		{
			System.out.print("I am flying");
		}
		void sing()
		{
			System.out.println("I am singing");
		}
	}
	
	
	public class Solution
	{
		public static void main(String[] args)
		{

		   Bird bird = new Bird();
		   bird.walk();
		   bird.fly();
		   bird.sing();
		}
	 }

OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/a7803208-cea5-4c2d-86d2-9917145ae3d7)

CONCLUSION:

	The java program to explain inheritance is written,compile,executed and the desired output is obtained successfully.

