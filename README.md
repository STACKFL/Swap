import java.util.*;
public class STN
{
public static void main(String[] args) 
{
	int x=0,y=0;	
	Scanner ss=new Scanner(System.in);
	System.out.println("Enter number to Print :");	
	x=ss.nextInt();
	System.out.println("Enter number to Print :");	
	y=ss.nextInt();
	x=x+y;
	y=x-y;
	x=x-y;
	System.out.println("X="+x+" y="+y);
}
}	
