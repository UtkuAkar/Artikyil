# Artikyil

import java.util.Scanner;
public class Artikyil {
    public static void main(String[] args) {

        int yil,sonuc;
        Scanner input = new Scanner(System.in);
        System.out.print(" Yıl giriniz : ");
        yil = input.nextInt();
        sonuc=yil/4;

        if(yil%100!=0 ){
            if (yil%4==0){

            System.out.println("Artık yıldır " + yil);
            }
            else {
                System.out.println("Artık Yıl Değildir "+yil);
            }
        }
        if(yil%100==0 ){
            if (yil%400==0){

                System.out.println("Artık yıldır " + yil);
            }
            else {
                System.out.println("Artık Yıl Değildir "+yil);
            }
        }


    }
}

