Allahindus


 Console.WriteLine("Sisesta ostusumma");
 double ostusumma = double.Parse(Console.ReadLine());
 if (ostusumma > 100)
 {
     Console.WriteLine("Saad 20% allahindlust!!!!!!!!!!!!!!!!!!!!!!!!!!!!!");
 }
 else if (ostusumma < 101 && ostusumma > 50)
 {
     Console.WriteLine("Saad 10% allahindlust. c: yay");
 }
 else if (ostusumma < 51 && ostusumma > 20)
 {
     Console.WriteLine("5% allahindlust.");
 }
 else if (ostusumma < 21 && ostusumma > 0)
 {
     Console.WriteLine("allahindlust ei saa");
 }
 else
 {
     Console.WriteLine("sisestatud on vigane arv");
 }

