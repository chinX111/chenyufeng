package hello;

import java.util.Scanner;

public class Hello {

	public static void main(String[] args) {
//		 TODO Auto-generated method stub
		System.out.println("你好");
		Scanner A = new Scanner(System.in);
//		int price;
//		price=A.nextInt();
		System.out.println(A.nextInt());
		int x=10;
		int a=x++;
		System.out.println("a="+a);
		System.out.println("x="+x);
		x++;
		System.out.println("x1="+x);
		++x;
		System.out.println("x2="+x);
		int b=++x;
		System.out.println("b="+b);
		System.out.println("x="+x);
		int c=x--;
		System.out.println("c="+c);
		System.out.println("x="+x);
		int d=--x;
		System.out.println("d="+d);
		System.out.println("x="+x);
	}

}
