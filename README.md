# postv_negatv
import java.util.Scanner;
public class Postive_Negative 
{
public static void main(String[] args) 
{
Integer m;
Scanner s = new Scanner(System.in);
System.out.print("Enter the number:");
m = s.nextInt();
if(m > 0)
{
 System.out.println("The given number "+m+" is Positive");
}
 else if(m < 0)
{
System.out.println("The given number "+m+" is Negative");
 }
else
{
System.out.println("The given number "+m+" is neither Positive nor Negative ");
}
}
}
