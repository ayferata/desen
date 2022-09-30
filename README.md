# desen
import java.util.Scanner;
public class Desen {
    static void desen(int n){
        if(n>0) {
            System.out.print(n);
            desen(n - 5);
        }
        System.out.println(n);
    }
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        System.out.print("N sayı : ");
        int n =input.nextInt();
        desen(n);
    }
}
