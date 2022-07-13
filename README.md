# Artik-yil-hesaplama
www.patika.dev   Artık Yıl hesaplama



        import java.util.Scanner;

        public class Artik_yil {
        public static void main(String[] args) {
        Double year;
        System.out.println("Lutfen Yil Giriniz:");
        Scanner input = new Scanner(System.in);
        year = input.nextDouble();

        if (year % 4 == 0) {
            if ((year % 100 == 0) && (year % 400 == 0)) {
                System.out.println(year + " Bir artik yildir!");
            } else if (year%100!=0) {
                System.out.println(year + " Bir artik yildir!");
            } else {
                System.out.println(year + " Bir artik yil degildir..");
            }
        }else {
            System.out.println(year + " Bir artik yil degildir..");
        }
    }
}
