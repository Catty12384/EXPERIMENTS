AIM:
	
	To write a java program to print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee'.
	
ALGORITHM:

	STEP-1 : Create a class named Employee.
	STEP-2 : Declare the variables required.
	STEP-3 : Create a constructor for the class Employee with the required parameters.
	STEP-4 : Assign the variables with their values.
	STEP-5 : Create a function for each employee.
	STEP-6 : Create a class named EmployeeDetails.
	STEP-7 : Create a main function.
	STEP-8 : Create objects and pass arguments for functions.
	STEP-9 : Call the function.
PROGRAM:
	
	class Employee
	{
		String Name;
		int Year;
		String Address;
		Employee(String nam,int years, String addr)
		{
			Name=nam;
			Year=years;
			Address=addr;
		}
		void Sam()
		{
			System.out.println(Name+ " " +Year + " " +Address);
		}
		void Robert()
		{
			System.out.println(Name+ " " +Year + " " +Address);
		}
		void John()
		{
			System.out.println(Name+ " "+Year + " " +Address);
		}
	}
	class EmployeeDetails
	{
		public static void main(String args[])
		{
			System.out.println("Name" + " Year of Joining " + "Address" );
			Employee e=new Employee("Sam", 2000, "68D-WallsStreet");
			e.Sam();
			Employee e1=new Employee("Robert", 1994, "64C-WallsStreet");
			e1.Robert();
			Employee e2=new Employee("John", 2002, "70F-WallsStreet");
			e2.Sam();
		}
	}

CONCLUSION:

	The java program to print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee' is written, compiled, executed and the desired output is obtained successfully.
