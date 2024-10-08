import java.io.*;
import java.util.*;
class Circle {
    double r;
    Circle() {
        r = 0;
    }
    Circle(double r) {
        this.r = r;
    }
    Circle(Circle ob) {
        this.r = ob.r;
    }
    double area() {
        return Math.PI * r * r;
    }
   double area(double r) {
        return Math.PI * r * r;
    }
    void set_circle(double r) {
        this.r = r;
    }
}
public class Main {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        Circle c1 = new Circle();
        System.out.println("After default constructor, Area of first circle is: " + c1.area());
        System.out.println("Enter radius of first circle:");
        double radius = sc.nextDouble();
        c1.set_circle(radius);
        System.out.println("Now area of first circle is: " + c1.area());
        Circle c2 = new Circle(8.8);
        System.out.println("Area of second circle is: " + c2.area());
        Circle c3 = new Circle(c2);
        System.out.println("Area of third circle is: " + c3.area());
        System.out.println("Area of first circle with radius 7.0 is: " + c2.area(7.0));
    }
}
