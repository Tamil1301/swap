import java.util.Scanner;
public class Swap2{
   public static void main(String[]args)
   {
    int x=10,y=200;
    System.out.println("Before Swap");
    System.out.println("x="+x);
    System.out.println("y="+y);
    int temp=x;
    x=y;
    y=temp;
    System.out.println("After Swap");
    System.out.println("x="+x);
    System.out.println("y="+y);
   }
}
