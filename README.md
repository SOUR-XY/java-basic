# java-basic
1-1
package welcome;

public class welcome {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
       System.out.println("Welcome to java!");
	}

}

1-2
package debug;

public class debug {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
       System.out.println("Program is fun");
       System.out.println("Fundamentals first");
       System.out.println("problem driven");
	}

}

1-3
package debug;

public class debug {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
       System.out.println((10.5 + 2 * 3) / (45 - 3.5));
	}
}

2-1
package debug;

public class debug {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		double radius = 20;
	    double area;
	    area = radius * radius * 3.1415;
	    System.out.println("the area for the circle of radius"+radius+" is "+area);
	}
}

2-2
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
       Scanner input = new Scanner(System.in);
       System.out.print("Enter a number for radius:");
       double radius = input.nextDouble();
       double area = radius * radius * 3.14159;
       System.out.println("the area for the circle of radius "+ radius + " is " +area);
	}
}

2-3
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("Enter three numbers: ");
		double number1 = input.nextDouble();
		double number2 = input.nextDouble();
		double number3 = input.nextDouble();
		double average = (number1 + number2 + number3) / 3;
		System.out.println("The average of "+ number1 + " " + number2 + " " + number3 + " is "+ average);
		}
}

2-4
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		final double pi = 3.14159;
		Scanner input = new Scanner(System.in);
		System.out.print("Enter a number of radius: ");
		double radius = input.nextDouble();
		double area = radius * radius * pi;
		System.out.println("The area for the circle of radius " + radius + " is " + area);
                }
}

2-5
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("Enter an integer for seconds: ");
		int seconds = input.nextInt();
		int minutes = seconds / 60;
		int remainingSeconds = seconds % 60;
		System.out.println(seconds + " seconds is " + minutes + " minutes and " + remainingSeconds + " seconds");
        }
}

2-6
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("Enter a degree in Fa: ");
		double fa = input.nextDouble();
		double cel = (5.0 / 9) * (fa - 32);
		System.out.println("fa "+ fa + " is " + cel + " in cel");
        }
}

2-7
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		long totalmilliseconds = System.currentTimeMillis();
		long totalseconds = totalmilliseconds / 1000;
		long currentsecond = totalseconds % 60;
		long totalminutes = totalseconds / 60;
		long currentminute = totalminutes % 60;
		long totalhours = totalminutes / 60;
		long currenthour = totalhours % 24;
		System.out.println("Current time is " + currenthour + ":" + currentminute + ":" + currentsecond + " GMT");
        }
}

2-8
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("Enter purchase amout: ");
		double purchaseAmount = input.nextDouble();
		double tax = purchaseAmount * 0.06;
		System.out.println("Sales tax is $" + (int)(tax * 100) / 100.0);
        }
}

2-9
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("enter annual interest rate, e.g.,7.25%: ");
		double a =input.nextDouble();
		double m = a / 1200;
		System.out.print("Enter number of years as an integer, e.g., 5: ");
		int n = input.nextInt();
		System.out.print("Enter loan amount e.g., 120000.95");
		double l = input.nextDouble();
		double mp = l * m / (1 - 1 / Math.pow(1 + m,n * 12));
		double tp = mp * n *12;
		System.out.println("the monthly payment is $" + (int)(mp *100) / 100.0);
		System.out.println("The total payment is $" + (int)(tp * 100 ) / 100.0);
        }
}

2-10
package hello;

import java.util.Scanner;

public class helloo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		System.out.print("enter an amount in double: ");
		double amount =input.nextDouble();
		int ra = (int)(amount * 100);
		int no = ra / 100;
	    ra = ra % 100;
	    int nq = ra / 25;
	    ra = ra % 25;
	    int nd = ra / 10;
	    ra = ra % 10;
	    int nn = ra / 5;
	    ra = ra / 5;
	    int np = ra;
		System.out.println("your amout " + amount + "consists of");
		System.out.println(" " + no + " dollsrs");
		System.out.println(" " + nq + " quarters");
		System.out.println(" " + nd + " dimes");
		System.out.println(" " + nn + " nickels");
		System.out.println(" " + np + " pennies");
        }
}
