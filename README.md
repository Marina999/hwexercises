# hwexercises
package AreaofaCircle;

import java.util.Scanner;

public class AreaofaCircle1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
				
				int Radius;
				Scanner inputRadius = new Scanner(System.in);
				System.out.println("Input Radius:");
				Radius = inputRadius.nextInt();
				System.out.println("The radius is: " + Radius + ". The area of a circle is: " + Math.PI * Math.pow(Radius,  2));
				
			
	}

}
