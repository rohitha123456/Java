import java.io.*;
import java.util.*;
public class LinearSearch{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        int pos=-1;
        System.out.println("Enter no of elements in array: ");
        int n=sc.nextInt();
        int arr[]=new int[n];
        System.out.println("Enter "+n+" elements in the array: ");
        for(int i=0;i<n;i++)
        {
            arr[i]=sc.nextInt();
        }
        System.out.println("Enter the key element to be searched: ");
        int key=sc.nextInt();
        for(int i=0;i<n;i++){
            if(arr[i]==key){
                pos=i+1;
                break;
            }
        }
        if(pos==-1){
            System.out.println("Element not found");
        }
        else{
            System.out.println(key+" Element found at "+pos);
        }
    }
}
