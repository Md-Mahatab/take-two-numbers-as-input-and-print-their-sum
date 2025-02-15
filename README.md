# take-two-numbers-as-input-and-print-their-sum
I input 2 numbers and always get there sums
My code :

package com.mycompany.mavenproject2;

import java.util.Scanner;

public class Mavenproject2 {

    public static void main(String[] args) {
        
      Scanner input = new Scanner(System.in);  
      int num1,num2,result;
      
        System.out.print("Enter first numbers = ");
        num1 = input.nextInt();
      
         System.out.print("Enter second  numbers = ");
        num2 = input.nextInt();
        
      result = num1 + num2;
      
        System.out.println("sum = "+result);    
    }
}
