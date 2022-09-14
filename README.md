# Ex04-Constructor
## Aim:
 To write a C# program to calculate the salary of an employee by passing the name, designation, noofexperience, basic salary and insurance amount through constructor.
 
 ## Algorithm:
 ### Step1:
 
 
 
 ## Program:
 ~~~
using System;
namespace abhi
{
    public class program
    {
        static void Main(String[] args)
        {
            string nam, desig;
            int exp, bs, ins,hra,ta,s;
            void salary(int bs, int ins)
            {
                
                hra = (20 * bs) / 100;
                ta = (10 * bs) / 100;
                s = bs + hra + ta - ins;
            }
            void display()
            {
                Console.WriteLine("Name of the employee is " + nam + " having " + exp + "years of experience , working as " + desig + " receives " + s + " of salary");
            }
            
            Console.WriteLine("Enter name: ");
            nam = Console.ReadLine();
            Console.WriteLine("Enter designation: ");
            desig = Console.ReadLine();
            Console.WriteLine("Enter the years of experience: ");
            exp = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter the basic salary: ");
            bs = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter insurance: ");
            ins = Convert.ToInt32(Console.ReadLine());
            salary(bs, ins);
            display();


        }
    }
}
 ~~~
 
 ## Output:
 ![image](https://user-images.githubusercontent.com/66360846/190063593-d3ee4ddd-5718-4a91-92e7-5a03175be944.png)

 
 ## Result:
