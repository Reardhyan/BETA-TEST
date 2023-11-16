# BETA-TEST

import java.util.Scanner;

public class MenuUtama {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int pilihan;
        do {
            System.out.println("Menu Utama :");
            System.out.println("1. Input Data");
            System.out.println("2. Tampilkan Data");
            System.out.println("3. Distribusi Frekuensi");
            System.out.println("4. Statistik");
            System.out.println("5. Keluar");
            System.out.print("Masukkan pilihan Anda: ");
            pilihan = input.nextInt();
            switch (pilihan) {
                case 1:
                    System.out.println("Anda memilih Input Data");
                    break;
                case 2:
                    System.out.println("Anda memilih Tampilkan Data");
                    break;
                case 3:
                    System.out.println("Anda memilih Distribusi Frekuensi");
                    break;
                case 4:
                    System.out.println("Anda memilih Statistik");
                    break;
                case 5:
                    System.out.println("Anda memilih Keluar");
                    break;
                default:
                    System.out.println("Pilihan tidak valid");
                    break;
            }
        } while (pilihan != 5);
    }
}
