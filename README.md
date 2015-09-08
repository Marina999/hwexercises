# hwexercises
package discountprices;

import java.util.Scanner;

public class discountprices3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		

		

				
				int Customer;
				Scanner inputCustomer = new Scanner(System.in);
				System.out.println("Purchase Amount before Discount: ");
				Customer = inputCustomer.nextInt();
				if(Customer>1000)
				{ int dis;
				  int fin;
				 
				  dis= Customer/10;
			      fin = Customer - dis;
			    
				if(Customer>1000) 
					
				System.out.println("Discounted Price: $" + fin);
				
				
				}
				else
				System.out.println("Please, pay: $" + Customer);
				
	    		

	    	}
			
				
	}
				
					 
	
