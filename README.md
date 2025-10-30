# A-simple-calculator-on-java
It is a simple calculator. It takes 2 numbers as inputs and an operator to do calculation 

import java.util.*;
public class meow 
{
    public static void main(String args[])
    {
        Scanner in=new Scanner(System.in);
        int a,b;
        char c;
        double d=0.0;
        System.out.println("Enter a number");
        a=in.nextInt();
        System.out.println("Enter a number");
        b=in.nextInt();
        System.out.println("Enter an operator *,/,+,- ");
        c = in.next().charAt(0);
        switch(c)
        {
         case '+':
         d=a+b;
         System.out.println(d);
         break;
         case '-':
         d=a-b;
         System.out.println(d);
         break;
         case '*':
         d=a*b;
         System.out.println(d);
         break;
         case'/':
         d=a/b;
         System.out.println(d);
         break;
         default:
         System.out.println("get lost loser.");
         break;
        }
    }
}
