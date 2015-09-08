# hwexercises
package dollarsintocentsgame;

import java.util.Scanner;

public class dollarsintocents {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		       int user;
		       int dollars;
		       int cents;
		       Scanner inputuser = new Scanner(System.in);
		       System.out.println("Input cents:");
		       user = inputuser.nextInt();
		       dollars = user/100;
		       cents = user%100;
		       
		       
		       int inputNumber;
		       int calculatedAnswer;

		       
		    
		       
		       System.out.println ("The Cents entered equal: $"+ dollars +"."+ cents);
		    }
		
	}


