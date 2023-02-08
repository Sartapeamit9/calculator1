# calculator1
package forLoop;

import java.util.Scanner;
public class Calculator
    {
public static void main(String[] args)
            {
	Scanner reader=new Scanner(System.in);
	System.out.println("############################CODE FOR CALCULATOR#############################");
  System.out.println("To perform operation please enter two Numbers\n\n::);
  
	double frist=reader.nextDouble();
	double second=reader.nextDouble();
	System.out.println("+,-,*,/");
	char operator=reader.next().charAt(0);
	double result;
	
	switch(operator)
	{
	case'+':
		result=frist+second;
		System.out.println(result);
		break;
	case'-':
		result=frist-second;
		System.out.println(result);
		break;
	case'*':
		result=frist*second;
		System.out.println(result);
		break;
	case'/':
		result=frist/second;
		System.out.println(result);
		break;
		
			
		default:
			System.out.println("Error ! Opearator is not correct");
			return;
			
	
	
               	}
			
			
	
		
	}
	
	
	
	
	
}
