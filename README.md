# Y-ld-zlar-ile-gen-Yap-m-
www.patika.dev
--------------------------


import java.util.Scanner;

public class YıldızUcgen {
	
    public static void main(String[] args) {
        int boyut = 5;
        int bosluk = boyut - 1;

        
        for (int i = 0; i < boyut; i++) {
            for (int j = 0; j < bosluk; j++) {
                System.out.print(" ");
            }
            for (int k = 0; k < 2 * i + 1; k++) {
                System.out.print("*");
            }
            bosluk--;
            System.out.println();
        }

        
        bosluk = 1;
        for (int i = 0; i < boyut - 1; i++) {
            for (int j = 0; j < bosluk; j++) {
                System.out.print(" ");
            }
            for (int k = 0; k < 2 * (boyut - i - 1) - 1; k++) {
                System.out.print("*");
            }
            bosluk++;
            System.out.println();
        }
    }
}

