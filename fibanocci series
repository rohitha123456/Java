import java.io.*;
import java.util.*;
public class FibRec{
    int fib(int x){
        if(x==0){
            return 0;
        }
        else if(x==1){
            return 1;
        }
        else{
            return(fib(x-1)+fib(x-2));
        }
    }
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        FibRec ob=new FibRec();
        System.out.println("Enter n value: ");
        int n=sc.nextInt();
        System.out.println("The fibonacci sequence is ");
        for(int i=0;i<n;i++){
            System.out.println(ob.fib(i));
        }
    }
}
