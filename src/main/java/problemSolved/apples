import java.util.Scanner;
/** ProblemSolved.java by F. M. Carrano
 
   Computes the money saved by buying a box of apples 
   at the box rate instead of the individual rate.
 
   Input:  Number of apples per box
           Cost of one apple
           Cost of box of apples
 
   Output: The input data
           The cost of apples if bought separately
           The savings if bought by the box
*/
public class ProblemSolved
{
   public static void main(String[] args)
   {
      Scanner keyboard = new Scanner(System.in);
      System.out.print("How many apples are in a box? ");
      int applesPerBox = keyboard.nextInt();

      System.out.print("How much does one apple cost? $");
      double costPerApple = keyboard.nextDouble();

      System.out.print("How much does a box of apples cost? $");
      double costPerBox = keyboard.nextDouble();

      double costOfApples = applesPerBox * costPerApple;
      double savings = costOfApples - costPerBox;

      System.out.println();
      System.out.println("Apples per box:                       " + 
                         applesPerBox);
      System.out.println("Cost per apple:                      $" + 
                         costPerApple);
      System.out.println("Cost per box:                        $" + 
                         costPerBox);
      System.out.println("Cost of apples if bought separately: $" + 
                         costOfApples);
      System.out.println("Savings if bought by the box:        $" + 
                         savings);
   } // End main
} // End ProblemSolved
