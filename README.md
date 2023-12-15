


/*Write a C# Sharp program to exchange the first and last characters in a given string and return the new string.

Sample Input:
"abcd"
"a"
"xy"
Expected Output:

dbca
a
yx
*/
namespace SIVA
{
    class Program
    {
        static void Main(string[] args)
        {
            do
            {
                string a = Console.ReadLine();
                if (a.Length <= 1)
                    Console.WriteLine(a);
                else
                    Console.WriteLine(program(a));
            }
            while(true);

        }

            static string program(string a)
            {
                return (a[a.Length-1] + a.Substring(1,a.Length-2) + a[0]);
              
            }

        }
   
        

    
}
