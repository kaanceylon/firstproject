



























import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
      int mat, fizik, turkce, muzik, tarih;
      Scanner input = new Scanner(System.in);
      System.out.print("mat notunu gir.");
        mat = input.nextInt();
        System.out.print("fizik notunu gir.");
        fizik = input.nextInt();
        System.out.print("turkce notunu gir.");
        turkce = input.nextInt();
        System.out.print("muzik notunu gir.");
        muzik = input.nextInt();
        System.out.print("tarih notunu gir.");
        tarih = input.nextInt();



        int toplam = (mat + fizik + turkce + muzik + tarih);
        double sonuc = toplam / 5;
        System.out.println("Not Ortalamaniz : " + sonuc);

        String durum = sonuc > 60 ? "Sınıfı Geçti" : "Sınıfta Kaldı";

        System.out.println(durum);
