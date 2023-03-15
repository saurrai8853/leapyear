# leapyear
Using this code user can check year is leap year or not
package mypackage;

import java.util.Scanner;

public class LeapYearOrNot{

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		System.out.print("Enter your year:");
		int year=sc.nextInt();
         if((year%4==0&&year%100!=0)||(year%400==0)) {
        	 System.out.print("leap year:"+year);
        	 
         }
	else {
        	 System.out.print("not a leap year:"+year); 
         }
	}

}

