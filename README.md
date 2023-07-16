# Temperature

package temperature;

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
	
		int temperature;
		
		Scanner inp = new Scanner(System.in); 
		
		System.out.println("Enter the temperature:");
		temperature = inp.nextInt();
		
		if (temperature < 5) {
			System.out.println("Go skiing"); }
		
		
		else if (temperature >= 5  && temperature <15) {
			System.out.println("Go to the cinema"); } 
		 
		
		else if (temperature >= 15 && temperature < 25) {
			System.out.println("Go have a picnic"); }
			
		
		else {
			System.out.println("Go swimming"); }
		
   }

	}


