# Midterm-Q1

import java.util.Arrays;
import java.util.Scanner; 

public class readNumbers {



	public static void main (String args[]) {
		Scanner input = new Scanner(System.in);
		Scanner length = new Scanner(System.in);

		System.out.println("What is the array size: ");
		
		int len=length.nextInt();
		int[] numbers = new int[len];
		
		for (int i = 0; i < numbers.length; i++)
		{
			System.out.println("Please enter number");
			numbers[i] = input.nextInt();

		}

		System.out.println(Arrays.toString(numbers));


	}
}
