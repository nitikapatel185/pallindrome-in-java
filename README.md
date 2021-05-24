# pallindrome-in-java
package firstproject;
import java.util.*;
public class Pallindrome {
public static void main(String args[]) {
	int n,c,r,s=0;
	Scanner input =new Scanner(System.in);
	System.out.println("Enter any number n=");
	n=input.nextInt();
	c=n;
	while(n>0)
	{
		r=n%10;
		s=(s*10)+r;
		n=n/10;
	}
	if(c==s)
		System.out.println("Pallindrome");
		else
			System.out.println("Not Pallindrome");
}
}
