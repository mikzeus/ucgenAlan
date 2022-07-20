# ucgenAlan
üçgenin alanını klavyeden sayı girerek hesaplama aracıdır.
package odev;

import java.util.Scanner;

public class ucgenAlan {
    public static void main(String[] args) {

        int a, b, c;
        double alan,u;


        Scanner kenar = new Scanner(System.in);

        System.out.println("birinci kenarı giriniz:");
        a=kenar.nextInt();

        System.out.println("ikinci kenarı giriniz: ");
        b=kenar.nextInt();

        System.out.println("ucuncu kenarı giriniz:");
        c= kenar.nextInt();

        u = (a+b+c)/2;
        alan =  u * (u - a) * (u - b) * (u - c);

        System.out.println("ucgenin alanı: " +alan*alan);


    }
}
