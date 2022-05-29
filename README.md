# MukemmelSayi

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        System.out.println("Sayıyı Giriniz :  ");
        int total = 0;
        int num = input.nextInt();
        for (int i = 1; i < num; i++) {
            if (num % i == 0) {
              total=total+i;
            }
        }
        if (total==num){
            System.out.println(num+ "Mükemmel Sayıdır. " );
        }else{
            System.out.println(num+ "Mükemmel Sayı Değildir. ");
        }
    }
}
