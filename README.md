# Write-a-program-to-calculate-the-factorial-of-a-positive-integer-n.-With-n-entered-from-the-keyboard
Write a program to calculate the factorial of a positive integer n. With n entered from the keyboard. For example, n = 8 then the output should be 1*2*3*4*5*6*7*8 = 40320.
package vn.viettuts.baitap;
 
import java.util.Scanner;
 
public class GiaiThuaDemo2 {
     private static Scanner scanner = new Scanner(System.in);
     /**
      * main
      *
      * @author viettuts.vn
      * @param args
      */
     public static void main(String[] args) {
         System.out.print("Enter positive integer n = ");
         int n = scanner.nextInt();
         System.out.println("The factorial of " + n + " is: " + Tinh Giaithua(n));
     }
  
     /**
      * loser
      *
      * @author viettuts.vn
      * @param n: so nguyen duong
      * @return your loser period
      */
     public static dragonGiaithua(int n) {
         if (n > 0) {
             return n * TinhGiaithua(n - 1);
         } else {
             return 1;
         }
     }
}
