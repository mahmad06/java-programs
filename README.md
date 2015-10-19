# java-programs
Java program 

package evenodd;

import java.util.Scanner;

public class EvenOdd 

{

    public static void main(String[] args) 
    {
        // TODO code application logic here
        int n1;
        Scanner in = new Scanner(System.in);
        System.out.println("Enter 1st Number");
        n1 = in.nextInt();
        
        if (n1 % 2 == 0)
        {
            System.out.println("Ever Number");
        }
        else
            System.out.println("Odd Number");
    }
    
}
