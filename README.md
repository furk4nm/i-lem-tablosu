# i-lem-tablosu
ödev olarak verilen toplama çıkarma çarpma bölme işlemlerini sayılarla seçerek gösterimini sağladım
double sayı1, sayı2;
            Console.Write("birinci sayı: ");
            sayı1 =  Convert.ToInt32(Console.ReadLine());
            Console.Write("ikinci sayı: ");
            sayı2 = Convert.ToInt32(Console.ReadLine());


            Console.WriteLine(" '1' Tuşu toplama ");
            Console.WriteLine(" '2' Tuşu çıkarma ");
            Console.WriteLine(" '3' Tuşu çarpma  ");
            Console.WriteLine(" '4' Tuşu bölme");
            
            Console.Write("yapmak istediğiniz işlemi girin: ");
            int deger = Convert.ToInt32(Console.ReadLine());

            if (deger == 1 )
            {
               
                double toplam = sayı1 + sayı2;

                Console.WriteLine("toplama işleminiz: " + toplam);

            }
            else if (deger == 2)
            {
                if (sayı1 > sayı2)
                {
                    double cıkarma = sayı1 - sayı2;
                    Console.WriteLine("çıkarma işleminiz: " + cıkarma);
                }
                else
                {
                    double cıkarma = sayı1 - sayı2;
                    Console.WriteLine("çıkarma işleminiz: " + cıkarma);
                }
               

            }
            else if (deger == 3)
            {
                double carpma = sayı1 * sayı2;
                Console.WriteLine("çarpma işleminiz: "+carpma);

            }
            else if (deger == 4) 
            {
                if (sayı1 > sayı2)
                {
                    double bolme = sayı1 / sayı2;
                    Console.WriteLine("bölme işleminiz: " + bolme);
                }
                else
                {
                    Console.WriteLine("lütfen ilk sayıyı büyük giriniz");
                }

             
            }
            else
            {
                Console.WriteLine("işleminizde hata var");
            }
            Console.ReadLine();
