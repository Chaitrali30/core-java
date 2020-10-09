# core-java
 Java Calculator
 package statement;
import java.util.*;
public class Stwitch {

	public static void main(String[] args) {
		
Scanner sc= new Scanner(System.in);
System.out.println("Enter First No: ");
int a =sc.nextInt();

System.out.println("Enter Second  No: ");
int b =sc.nextInt();

System.out.println("Enter The Operation: ");
sc.nextLine();
char Operation =sc.nextLine().charAt(0);

int result =0;

switch (Operation)
{case '+':
	result=a+b;
	System.out.println("Answer is " +result);
break;

case '-':
	result=a-b;
	System.out.println("Answer is "  +result);
break;

case '*':
	result=a*b;
	System.out.println("Answer is "  +result);
break;

case '/':
	result=a/b;
	System.out.println("Answer is "  +result);
break;

case '%':
	result=a%b;
	System.out.println("Answer is"  +result);
break;
default:
	System.out.println("INVALID OPERATION!!!");
}
	}

}
