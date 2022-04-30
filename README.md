# Find-vowels
Simple java program to find vowels in a entered text 
import java.util.Scanner;

public class Q1{

	public static void main(String[] args) {
		System.out.print(" Enter the text: ");
		Scanner sun = new Scanner(System.in);
		String txt = sun.nextLine();
		
		
		int numOfVowels = 0;
		
		for(int i=0; i<txt.length(); i++)
		{
			if(txt.charAt(i) == 'a' || txt.charAt(i) == 'e' || txt.charAt(i) == 'i' || txt.charAt(i) == 'o' || txt.charAt(i) == 'u' || txt.charAt(i) == 'A' || txt.charAt(i) == 'E' || txt.charAt(i) == 'I' || txt.charAt(i) == 'O' || txt.charAt(i) == 'U')
			{
				numOfVowels = numOfVowels + 1;
			}
		}
		
		System.out.println("Number of vowels: " + numOfVowels);
	}

}
