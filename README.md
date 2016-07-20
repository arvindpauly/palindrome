# palindrome
import java.util.Scanner;
public class palindrome {
	public static void main(String[]arg){
		Scanner ab=new Scanner(System.in);
		int reversenum;
		
		System.out.println("enter the number");
		int num=ab.nextInt();
		String str=new String();
		//System.out.println("enter the string");
		//str= ab.next();
		reversenum = reversenum(num);
		//String str2 = Stringrev(str);
		if(num==reversenum)
			{System.out.println("tne num is palindrome");
			}
			
	      else
		{
			System.out.println("the num is not a palindrome");
			
	}
		

		public static int reversenum(int num){
			
			int  a=0;
		while (num>0)
		{
			int x=num%10;
		    a=(a*10)+x;
			num=num/10;
		}
		
		return(a);
		}
		}
