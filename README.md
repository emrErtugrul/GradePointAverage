# GradePointAverage

import java.util.Scanner;

public class Class {
    public static void main(String[] args) {

        //değişkenleri tanımladık
        int mat,fizik,kimya,turkce,tarih,muzik;

        //Scanner sınıfını bir kez tanımladık
        Scanner inp = new Scanner(System.in);

        //Kullanıcıdan değerleri almak için

        System.out.println("Lütfen Matematik Notunuzu Giriniz: ");
        mat= inp.nextInt();

        System.out.println("Lütfen Fizik Notunuzu Giriniz: ");
        fizik= inp.nextInt();

        System.out.println("Lütfen Türkçe Notunuzu Giriniz: ");
        kimya= inp.nextInt();

        System.out.println("Lütfen Tarih Notunuzu Giriniz: ");
        turkce= inp.nextInt();

        System.out.println("Lütfen Müzik Notunuzu Giriniz: ");
        tarih= inp.nextInt();

        System.out.println("Lütfen Müzik Notunuzu Giriniz: ");
        muzik = inp.nextInt();

        int toplam = (mat + fizik + kimya+turkce+tarih+muzik);
        double sonuc = toplam/6;

        System.out.println("Ortalamanız: "+sonuc);

        //60 dan büyükse geçti, küçükse kaldı yazdırma

        System.out.println(sonuc >60 ? "Sınıfı Geçti" : "Sınıfta Kaldı");

    }
}

