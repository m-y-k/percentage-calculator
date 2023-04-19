# Percentage-calculator
Percentage and Result Calculator 


package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
	// write your code here
    /*
    Scanner sc = new Scanner(System.in);


    System.out.println("Enter Your Hindi Marks: ");
    int Hindi = sc.nextInt();
    System.out.println("Enter Your English Marks: ");
    int English = sc.nextInt();
    System.out.println("Enter Your Maths Marks: ");
    int Maths = sc.nextInt();
    System.out.println("Enter Your Science Marks: ");
    int Science = sc.nextInt();
    System.out.println("Enter Your Computer Marks: ");
    int Computer = sc.nextInt();
    System.out.println("choose out of which You want to know percentage: ");
        int total = sc.nextInt();

    float sum = Hindi + English + Maths + Science + Computer;
    float percent = ( sum / total ) * 100 ;
    System.out.println("Your Total Percentage: ");
        System.out.println(percent);
    */
    Scanner yusuf = new Scanner(System.in);
    System.out.println("Enter Your Physics Marks: ");
    byte s1 = yusuf.nextByte();
    System.out.println("Enter Your Chemistry Marks: ");
        byte s2 = yusuf.nextByte();
    System.out.println("Enter Your Maths Marks: ");
        byte s3 = yusuf.nextByte();
        System.out.print("Your total percentage is: ");
        float sum = (s1+s2+s3)/3.0f;
        System.out.println(sum);
    if (sum >= 40 && s1>=33 && s2>=33 && s3>=33) {
        System.out.print("Congrats! Your are promoted.");
    }
    else {
        System.out.print("OOps! Your are not promoted.");
    }

    }
}
