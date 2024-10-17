import java.io.*;
import java.util.Scanner;
public class PrimeNumbersInRange {
    public static void main(String[] args) {
        System.out.println("Enter range of prime numbers start and end:");
        Scanner sc=new Scanner(System.in);
        int start=sc.nextInt();
        int end=sc.nextInt();
        System.out.println("Prime numbers between " + start + " and " + end + ":");
        for (int i = start; i <= end; i++) {
            if (isPrime(i)) {
                System.out.println(i);
            }
        }
    }
    static boolean isPrime(int n) {
        if (n < 2) {
            return false; // 0, 1, and negative numbers are not prime
        }
        for (int i = 2; i < n; i++) {
            if (n % i == 0) {
                return false; // Check for divisors between 2 and n-1
            }
        }
        return true;
    }
}
