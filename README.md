# hackerRankDay3IntroToConditionalStatements
[Kodluyoruz](https://app.patika.dev/) .Net eğitimi için hazırlanan C# If-ElseIf-Ternary-If ödevidir. Hacker Rank Challenge Day 3: Intro to Conditional Statements cevabı için oluşturulmuştur.
## Day 3: Intro to Conditional Statements
- N'nin ikiye bölümünden kalanın 1 olması demek sayının tek sayı olacağı anlamına geldiği için ilk olarak N değişkenin modu alınmıştır.
- Konsola "Weird" yazdırmamız gereken diğer durum sayının 6 ve 20 arasında (6 ve 20 dahil) bulunan tek sayılar olacağı için veya operatörü (||) ile bu koşulda belirtilmiştir.
- Geri kalan tüm durumlar için sonuç "Not Weird" olacağından else bloğuda aşağıdaki gibi oluşturulmuştur.  
    
        if(N % 2 == 1 || (N >= 6 && N <= 20))
        {
            Console.WriteLine("Weird");
        }
        else
        {
            Console.WriteLine("Not Weird");
        }
         
- Görsel;
    ![Day 3 Intro to Conditional Statements Hacker Rank Gorseli](Day%203%20Intro%20to%20Conditional%20Statements%20Hacker%20Rank%20Gorseli.png)

### [Hacker Rank Profilim](https://www.hackerrank.com/ogulcan_celik24) 
#### https://www.hackerrank.com/ogulcan_celik24
#### www.patika.dev


