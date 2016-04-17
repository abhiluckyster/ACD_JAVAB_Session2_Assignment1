# ACD_JAVAB_Session3_Assignment1

import java.util.Scanner;
import java.lang.Math;

public class RootOfNo {
	public void calRoot(int num)
	{
		double root = Math.sqrt(num);
		double cubeRoot = Math.cbrt(num);
		System.out.println("Square root of" +num+" number is : "+root +" and cube root is : "+cubeRoot);
	}
	
	public static void main(String args[]){
		int num;
		RootOfNo rno = new RootOfNo();
		Scanner number=new Scanner(System.in);
		System.out.println("Enter number");
		num = number.nextInt();
		rno.calRoot(num);
		number.close();
	}
}
