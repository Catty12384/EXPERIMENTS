AIM:

	To write a program to get and print Employee details.
	
ALGORITHM:

	STEP-1 : Import Scanner class.
	STEP-2 : Create a class Member. 
	STEP-3 : Create a class Employee.
	STEP-4 : Create a class Office.
	STEP-5 : Declare the required variables.
	STEP-6 : Get the values of the variables.
	STEP-7 : Ask whether the person is a manager or an employee.
	STEP-8 : According to the choice call the function.
	
PROGRAM:

	import java.util.Scanner;
    public class Office
    {
    
        public static void main(String [] args) 
        {
            Scanner s=new Scanner(System.in);
            System.out.print("NAME: ");
            String name=s.nextLine();
            System.out.print("AGE: ");
            int age=s.nextInt();
            System.out.print("PHONE NUMBER: ");
            String ph=s.next();
            System.out.print("DEPARTMENT: ");
            String dept=s.next();
            System.out.print("SPECIALIZATION: ");
            String spec=s.next();
            System.out.print("ADDRESS: ");
            String addr=s.next();
            System.out.print("SALARY: ");
            int sal=s.nextInt();

            Manager m=new Manager();
            Employees e= new Employees();
            System.out.print("WHAT IS YOUR DESIGNATION:");
            String d=s.next();
            s.close();
            if(d.equals("Manager")||d.equals("manager"))
            {
                System.out.println("------------------------------------");
                m.manager(name,age,ph,addr,dept,spec);
                m.printSalary(sal);
            }
            else if(d.equals("Employee")||d.equals("employee"))
            {
                System.out.println("------------------------------------");
                e.employees(name,age,ph,addr,dept,spec);
                e.printSalary(sal);
            }
        }
    }
	
	
	public class Employees extends Member
	{
		String spec,dept;
		public void employees(String name,int age,String ph,String addr,String dept,String spec)
		{
			System.out.println("NAME: "+name);
			System.out.println("AGE: "+age);
			System.out.println("PHONE NUMBER: "+ph);
			System.out.println("DEPARTMENT: "+dept);
			System.out.println("SPECIALIZATION: "+spec);
		}
	}
	
	
	public class Manager extends Member
	{
		String spec,dept;
		public void manager(String name,int age,String ph,String addr,String dept,String spec)
		{
			System.out.println("NAME: "+name);
			System.out.println("AGE: "+age);
			System.out.println("PHONE NUMBER: "+ph);
			System.out.println("DEPARTMENT: "+dept);
			System.out.println("SPECIALIZATION: "+spec);
		}
	}
	
OUTPUT:

![image](https://github.com/Catty12384/EXPERIMENTS/assets/120629225/fc3368cb-6149-4fc5-b990-542a1e97e047)

CONCLUSION:

	The java program to get and print Employee details is written,compile,executed and the desired output is obtained successfully.

