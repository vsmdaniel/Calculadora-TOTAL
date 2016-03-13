# Calculadora-TOTAL

            double result;

            Console.WriteLine("Digite um número: ");
            double num1 = double.Parse(Console.ReadLine());
            
            Console.WriteLine("Escolha a operação");
            char opp = char.Parse(Console.ReadLine());

            Console.WriteLine("Digite outro número: ");
            double num2 = double.Parse(Console.ReadLine());


            if (opp == '+')

            {
                Console.ForegroundColor = ConsoleColor.Green;
                result = num1 + num2;
                Console.WriteLine("O resultado da operação é: " + result);


            }


            else
                if (opp == '-')

            {

                Console.ForegroundColor = ConsoleColor.Red;
                result = num1 - num2;
                Console.WriteLine("O resultado da operação é: " + result);


            }


            else
                if (opp == '*')

            {


                Console.ForegroundColor = ConsoleColor.Yellow;
                result = num1 * num2;
                Console.WriteLine("O resultado da operação é: " + result);


            } 


            else
                if (opp == '/')

            {

                Console.ForegroundColor = ConsoleColor.Cyan
                result = num1 / num2;
                Console.WriteLine("O resultado da operação é: " + result);


            }
