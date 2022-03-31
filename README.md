# Write-a-program-that-allows-you-to-input-3-numbers
The program will check these 3 numbers are 3 sides of a right triangle or not.
import java.util.Scanner;

public class BaiTapJavaCoBan4 {
    public static void main(String[] args)
    {
       float a, b, c;
       System.out.println("Enter 3 numbers:");
       Scanner sc = new Scanner(System.in);

       a = sc.nextFloat();
       b = sc.nextFloat();
       c = sc.nextFloat();

       if(a*a+b*b==c*c || b*b+c*c==a*a || c*c+a*a==b*b)
          System.out.println("Three correct numbers are the 3 sides of a right triangle");
       else
          System.out.println("Three numbers are not the sides of a right triangle");
    }
}
