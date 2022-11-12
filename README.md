# Not Ortalaması
##Not Ortalaması Hesaplayan Program


import java.util.Scanner;
public class Giriss {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
         int a, c;
        double b;
        System.out.println("mat notunu gir: ");
        a=input.nextInt();

        System.out.println("fizik notunu gir: ");
        b=input.nextDouble();

        System.out.println("tarih notunu gir: ");
        c=input.nextInt();
        double toplam= (a+b+c)/3;
        boolean topl =toplam>=60 ;
        String stri= topl? "Geçti" : "Kaldı";
        System.out.println(stri);
        System.out.println("ortalamaniz: " +toplam);

    }
}
