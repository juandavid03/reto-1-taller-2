# reto-1-taller-2
primera parte del taller (C1) programa que determina volumen y area




namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args)


        {
            double radio;
            double altura;
            Console.WriteLine("escriba la radio de la base en metros");
            string r = Console.ReadLine();
            radio = Convert.ToDouble(r);

            Console.WriteLine("escriba la altura del cilindro en metros");
            string a = Console.ReadLine();
            altura = Convert.ToDouble(a);

            double area = 2 * Math.PI * radio * altura;

            double volumen = (Math.PI * radio * radio * altura)/3;

            Console.WriteLine("el area del cilindro es de {0} mts cuadrados, y su volumen {1} mts cubicos", area, volumen);
            Console.ReadLine();
        }
    }
}
