# JavaSess4Ass4
package Basic;

import java.util.Scanner;

public class Sess4Ass4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String ori, rev = "";
		
		System.out.println("Enter the string to be reversed: ");
		Scanner scan=new Scanner(System.in);
		ori=scan.nextLine();
		
		int len=ori.length();
		for(int i=len-1;i>=0;i--){
			rev=rev+ori.charAt(i);
		}
		System.out.println("String reversed is: "+ rev);
	}

}
