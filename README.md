# Palindrome
package com.payilagamtest.java;

import java.util.Scanner;

public class PalindromeUser {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("WRITE ANY SENTENCE :");
		Scanner ss=new Scanner(System.in);
		String s=ss.next();
		String st="";
		for(int i=s.length()-1;i>=0;i--)
		{
			st+=s.charAt(i);
		}
		System.out.println(st);
		
		if(s.equals(st))
			System.out.println("this is palindrome");
		else
			System.out.println("this is not palindrome");

	}

}
