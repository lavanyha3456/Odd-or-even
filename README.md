# Odd-or-even
import java.util.Scanner;

public class OddOrEven {

public static void main(String[] args) {

Scanner scanner = new Scanner(System.in);

// Prompt the user to enter a number

System.out.print("Enter a number: ");

int number = scanner.nextInt();

// Check if the number is odd or even

if (number % 2 == 0) {

System.out.println("The number " + number + " is even.");

} else {

System.out.println("The number " + number + " is odd.");

}

scanner.close();
}
}
OUTPUT:

Enter a number: 19

The number 19 is odd.
