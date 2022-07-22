# java-d-ng-s-le-ortalama-hesablama
Java döngüler ile 0'dan girilen sayıya kadar olan sayılardan 3 ve 4'e tam bölünen sayıların ortalamasını hesaplayan programı yazınız.

   import java.util.Scanner;

    public class Main {

    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        int k, ortalama, toplam = 0, sayiAdedi = 0;


        System.out.print("Sayı Giriniz :");
        k = inp.nextInt();
        int i = 1;
        while (i >= 0 && i <= k) {
            if (i % 12 == 0) {
                toplam += i;
                sayiAdedi++;
            }
            i++;
        }
        ortalama = toplam / sayiAdedi;
        System.out.println("ortalamanız :" +ortalama);


     }
    }




