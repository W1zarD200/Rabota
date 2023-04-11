using System; 

using System.Collections.Generic; 

using System.Linq; 

using System.Text; 

using System.Threading.Tasks; 

 

namespace lb2 

{ 

    class Program 

    { 

        static void Main(string[] args) 

        { 

            Console.Write("Введите a: "); 

                double a = double.Parse(Console.ReadLine()); 

            double z1 = 1 - 1.0/ 4.0 * Math.Pow(Math.Sin(2*a),2) + Math.Cos(2*a); 

            double z2 = Math.Pow(Math.Cos(a), 2) + Math.Pow(Math.Cos(a), 4); 

            Console.WriteLine("z1=" + z1); 

            Console.WriteLine("z2=" + z2); 

            Console.ReadKey(); 

        } 

    } 

} 
