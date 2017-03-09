# Assignment1
My first project.
package javaassignment1;

import java.util.Scanner;
import static javax.swing.Spring.width;

/**
 *
 * @author Cody Fielding
 */
public class JavaAssignment1 {

    /**
     *
     */
    public static void main(String[] args) {
        // TODO code application logic here:
    System.out.println("My name is Cody and this is my project");
        
       Scanner scanner = new Scanner(System.in);
   System.out.println("Length of playing field");
    double Length =scanner.nextDouble();
   System.out.println("Width of playing field");
    double Width =scanner.nextDouble();
   Double area =Length*Width;
   System.out.println("Area of school playing field "+area +"cm²");
    }
    
}
