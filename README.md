import java.util.Scanner;

       public class CLASS {
           public static void main(String[] args) {
               int a, b, c;
               double u, alan;

               Scanner girdi = new Scanner(System.in);
               System.out.print("1.Kenari : ");
               a = girdi.nextInt();
               System.out.print("2.Kenari : ");
               b = girdi.nextInt();
               System.out.print("3.Kenari : ");
               c = girdi.nextInt();

               u = (a + b + c) / 2;

               System.out.println("Cevre: "+ u);

               alan = Math.sqrt((u - a) * (u - b) * (u - c));

               System.out.print("Alan: "+ alan);

