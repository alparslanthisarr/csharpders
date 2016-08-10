using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication8
{
    class Program
    {
        static void Main(string[] args)
        {
            int[,] dizi = new int[2, 2];
            dizi[0, 0] = 25;
            dizi[0, 1] = 35;
            dizi[1, 0] = 17;
            dizi[1, 1] = 77;

            for(int i = 0 ;i<=1;i++)
            {
                for (int j = 0; j <= 1; j++)
                {


                    Console.Write(" {0} ", dizi[i, j]);
                   
                }
                Console.WriteLine();

             
            }
            Console.Read();
            

        }
    }
}
