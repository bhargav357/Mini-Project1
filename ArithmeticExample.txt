import java.util.Scanner;

public class ArithmeticExample {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("enter the input 1");
		int n1=sc.nextInt();
		System.out.println("enter the input 2");
		int n2=sc.nextInt();
		
		int addition=n1+n2;
		int multiplication=n1*n2;
		double div=n1/n2;
		int sub=n1-n2;
		System.out.println("The Addtion is=:"+addition);
		System.out.println("The Subtraction is=:"+sub);

		System.out.println("The Multiplication is=:"+multiplication);
		System.out.println("The division is=:"+div);

	}

}
