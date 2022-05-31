import java.util.Scanner;

public class Armstrong {
public static void main(String[] args) {
	Scanner sc= new Scanner(System.in);
	System.out.println("ENTER a number");
	int n=sc.nextInt();
	int m=n;
	int r,s=0;
	while (n>0) {
		r=n%10;
		n=n/10;
		s=s+r*r*r;
	}
	if (s==m) {
		System.out.println("this is a armstrong number");
	}else {
		System.out.println("this is not a armstrong number");
	}
}
}
