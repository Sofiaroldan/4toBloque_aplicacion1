# 4toBloque_aplicacion1
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.IO;


namespace _4toBloque_aplicacion1
{
    class Program
    
            {
                static void Main(string[] args)
                {
                    Console.Write("ingrese el nombre de la ruta");
                    String ruta = Console.ReadLine() + ".txt";




                    StreamWriter ar;



                    ar = File.CreateText(ruta);




                    ar.Close();



                }
            }
        }
