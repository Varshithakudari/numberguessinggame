import java.util.Random;
import java.util.Scanner;

public class NumberGuessingGamenew{
    public static void main(String[] args) {
        // Create a new Scanner object for reading user input
        Scanner scanner = new Scanner(System.in);

        // Generate a random number between 1 and 100
        Random random = new Random();
        int numberToGuess = random.nextInt(100) + 1;

        // Initialize the user's guess
        int userGuess = 0;
        int numberOfTries = 0;

        // Game loop
        while (userGuess != numberToGuess) {
            System.out.println("Enter your guess (between 1 and 100): ");

            // Get the user's guess
            userGuess = scanner.nextInt();
            numberOfTries++;

            // Provide feedback on the guess
            if (userGuess < numberToGuess) {
                System.out.println("Your guess is too low.");
            } else if (userGuess > numberToGuess) {
                System.out.println("Your guess is too high.");
            } else {
                System.out.println("Congratulations! You've guessed the number!");
                System.out.println("It took you " + numberOfTries + " tries.");
            }
        }

        // Close the scanner
        scanner.close();
    }
}
