İmport java.util.Scanner;
public class Main {
        public static void main(String[] args) {
            
            int f,k,m,t,ta,mu; 
            Scanner fizik = new Scanner(System.in);
            System.out.println("Bir fizik sınav notunu giriniz: ");
            f=fizik.nextInt();
            System.out.println(f);

            
            Scanner kimya = new Scanner(System.in);
            System.out.println("Bir kimya sınav notunu giriniz: ");
            k=kimya.nextInt();
            System.out.println(k);

            
            Scanner matematik = new Scanner(System.in);
            System.out.println("Bir matematik sınav notunu giriniz: ");
            m=matematik.nextInt();
            System.out.println(m);

            
            Scanner turkce = new Scanner(System.in);
            System.out.println("Bir türkçe sınav notunu giriniz: ");
            t=turkce.nextInt();
            System.out.println(t);

            
            Scanner tarih = new Scanner(System.in);
            System.out.println("Bir tarih sınav notunu giriniz: ");
           ta=tarih.nextInt();
            System.out.println(ta);

            
            Scanner muzik = new Scanner(System.in);
            System.out.println("Bir müzik sınav notunu giriniz: ");
            mu=muzik.nextInt();
            System.out.println(mu);

            int toplam = (mu+m+t+ta+k+f);
            double sonuc= toplam/6.0;
            System.out.println(sonuc);

        


    }
}
