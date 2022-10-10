
   // 1

  int x=int.Parse(Console.ReadLine());
 
            Console.WriteLine(x/10);
            Console.WriteLine(x%10);
            Console.ReadLine();
            
    // 902
     int x = int.Parse(Console.ReadLine());
            if (x > 0 && x < 4)
            {
                Console.WriteLine("initial");
            }
            else if (x > 3 && x < 7)
            {
                Console.WriteLine("average");
            }
            else if (x > 6 && x < 11)
            {
                Console.WriteLine("sufficent");
            }
            else if (x>10 && x < 12)
                Console.WriteLine("high");
            Console.ReadLine();
            
            //903
            int x=int.Parse(Console.ReadLine());
            int y = x / 100;
            int z = (x % 100) % 10;
            if (y>z&&x>99&&x<1000)
            {
                Console.WriteLine(y);
            }
            else if (z>y&&x>99&&x<1000)
            {
                Console.WriteLine(z);
            }
            else if (y==z&&x>99&&x<1000)
                Console.WriteLine("=");
            Console.ReadLine();
            
            //906
              int num =int.Parse(Console.ReadLine());
            int x = num / 100;
            int y = (num % 100) / 10;
            int z = (num % 100) % 10;
            Console.WriteLine(x * y * z);
            Console.ReadLine();
            
            //4715 (YARIMCIQDIR)
             int n=int.Parse(Console.ReadLine());
            int x = (n - (n % 10 + n / 10)) / 9 + 1;
            Console.WriteLine(x);
            Console.ReadLine();
            
            //4716
               int n=int.Parse(Console.ReadLine());
            int k=int.Parse(Console.ReadLine());
            if (n < 1500 && k < 1500 && k > n&&k/n<5) 
            {
                Console.WriteLine(k / n);
            }

            Console.ReadLine();
            
           //4717
            int n = int.Parse(Console.ReadLine());
            int k = int.Parse(Console.ReadLine());
            if (n < 1500 && k < 1500 && k > n && k / n < 5)
            {
                Console.WriteLine(k%n);
            }
            Console.ReadLine();
            
            //4719
            int x1 = int.Parse(Console.ReadLine());
            int y1 = int.Parse(Console.ReadLine());
            int x2 = int.Parse(Console.ReadLine());
            int y2 = int.Parse(Console.ReadLine());
            if (x1 == x2)
            {
                Console.WriteLine("yes");
            }
            else if (y1 == y2)
            {
                Console.WriteLine("yes");
            }
            else
                Console.WriteLine("no");
            Console.ReadLine();
            
            //8599
            int num=int.Parse(Console.ReadLine());
            int x = num / 100;
            int y = (num % 100) / 10;
            int z = (num % 10) % 10;
            if (num > 99 && num < 1000)
            {
                Console.WriteLine(x);
                Console.WriteLine(y);
                Console.WriteLine(z);
            }
            Console.ReadLine();
            
            //8600
            int num=int.Parse(Console.ReadLine());
            int x = num / 10;
            int y = num % 10;
            if (num>9&&num<100)
            {
                Console.WriteLine(x+y);
                Console.WriteLine(x * y);  
            }
            Console.ReadLine();
            
            //8603
             int num=int.Parse(Console.ReadLine());
            int x = num / 100;
            int y = (num % 100) / 10;
            int z = (num % 100) % 10;
            if (num>99&&num<1000)
            {
                Console.WriteLine(x+y+z);
                Console.WriteLine(x*y*z);
            }
            Console.ReadLine();
            
            //8611
             int t= int.Parse(Console.ReadLine());
            if (t<0)
            {
                Console.WriteLine("ice");
            }
            else if (t>0)
            {
                Console.WriteLine("water");
            }
            Console.ReadLine(); 
            
            //8612
            int x =int.Parse(Console.ReadLine());
            int y1 = x * x * x + 2 * x * x + 4 * x - 6;
            int y2 = x * x * x - 7 * x;
            if (x>=0)
            {
                Console.WriteLine(y1);
            }
            else if (x<0)
            {
                Console.WriteLine(y2);
            }
            Console.ReadLine();
            
            //8613
            int x= int.Parse(Console.ReadLine());
            int y1 = 3 * x * x * x + 4 * x * x + 5 * x + 6;
            int y2 = 3 * x * x * x - 2 * x * x - 3 * x - 4;
            if (x >= 13)
            {
                Console.WriteLine(y1);
            }
            if(x<13)
            {
                Console.WriteLine(y2);
            }
            Console.ReadLine();
            
            //8800
             Console.WriteLine("Hello, Python");
             
            //eded oxu 
            
            int x = int.Parse(Console.ReadLine());
            int y = int.Parse(Console.ReadLine());
            if (x > 0 && y > 0)
            {
                Console.WriteLine("birinci rubdur");
            }
            else if (x < 0 && y > 0)
            {
                Console.WriteLine("ikinci rubdur");
            }
            else if (x < 0 && y < 0)
            {
                Console.WriteLine("ucuncu rubdur");
            }
            else if (x > 0 && y < 0) 
            {
                Console.WriteLine("dorduncu rubdur");
            }

            Console.ReadLine();
             
             //heftenin gunleri
             int gun=int.Parse(Console.ReadLine());
            if (gun == 1)
                Console.WriteLine("bazarertesi");
            else if (gun == 2)
                Console.WriteLine("cersenbe axsami");
            else if (gun == 3)
                Console.WriteLine("cersenbe");
            else if (gun == 4)
                Console.WriteLine("cume axsami");
            else if (gun == 5)
                Console.WriteLine("cume");
            else if (gun == 6)
                Console.WriteLine("senbe");
            else if (gun == 7)
                Console.WriteLine("bazar");
            else
                Console.WriteLine("bele gun yoxdur");
            Console.ReadLine();
            
            //median
             int x=int.Parse(Console.ReadLine());
            int y=int.Parse(Console.ReadLine());
            int z =int.Parse(Console.ReadLine());
            if (x > y && x > z && y > z)
            {
                Console.WriteLine(y);
            }
            else if (x < y && x < z && y < z)
            {
                Console.WriteLine(y);
            }
            else if (x > y && x < z && y < z)
            {
                Console.WriteLine(x);
            }
            else if (x < y && x > z && y > z)
            {
                Console.WriteLine(x);
            }
            else if (x > y && x > z && z > y)
            {
                Console.WriteLine(z);
            }
            else if (y > x && y > z && z > x)
            {
                Console.WriteLine(z);
            }
            Console.ReadLine();

             


           
