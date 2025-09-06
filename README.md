# T[Main.java](https://github.com/user-attachments/files/22188636/Main.java)
import java.util.*;
class Main {
    public static void main(String[] args) {
       Scanner sc=new Scanner(System.in);
		System.out.print("Enter no. of rows: ");
		int x=sc.nextInt();
		for (int i=1; i<=x; i++){
			for (int j=1; j<=i; j++){
				System.out.print("*");
			}
			System.out.println();
		}
    }
}
