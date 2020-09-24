# hello-world
NYIT:My hello-world repo
I'm USMC infantry veteran who is majoring in information technology at NYIT. 
I have always had a passion for computers and tech, and hope to see myself as a leader in the field one day.
__________________________________________________________________________________________________________________
package alpha;

public class info {

	public static void main(String[] args) {
				System.out.println("Name:Paul Wozlonis");
				System.out.println("Email:pwozloni@nyit.edu");
				System.out.println("Id:1201752");
		}
	}
  
 __________________________________________________________________________________________________________________ 
  package alpha;

public class integer_class_1 {
	public static void main(String[] args) {
        
        int first = 1;
        int second = 2;

        System.out.println("Enter two numbers: " + first + " " + second);
        int sum = first + second;

        System.out.println("The sum is: " + sum);
    }
}
__________________________________________________________________________________________________________________
package alpha;

import java.util.Scanner;

public class integer_class_2 {
	   public static void main(String[] args)   {
		   
	        Scanner input = new Scanner(System.in);
	        
	        System.out.print("Enter an integer: ");
	        int number = input.nextInt();
	        int first = 1;
	        
	        int sum = number + first;
	        
	        System.out.println("You entered " + sum);
	        
	       input.close();
	   }
}
