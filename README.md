# Float-or-Integer
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _4.Float_or_Integer
{
    class Program
    {
        static void Main(string[] args)
        {
            double num = double.Parse(Console.ReadLine());
            num = Math.Round(num);
            Console.WriteLine(num);
        }
    }
}
