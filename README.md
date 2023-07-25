import java.util.Scanner;
public class Main {
        public static void main(String[] args){
                Scanner input = new Scanner(System.in);
                double yaricap, alan, cevre, pi = 3.14;
                System.out.print("Yarı çapı giriniz :");
                yaricap = input.nextDouble();
                alan = pi * yaricap * yaricap ;
                cevre = 2 * pi * yaricap ;

                System.out.println("Alan :" + alan);
                System.out.print("Çevre :" + cevre) ;
        }
}
