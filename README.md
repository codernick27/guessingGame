// //nicholas Haug
// 04/22/2021
// printed weird when transferring to notepad to save! sorry!

import java.util.Scanner;
import java.util.Random;
import java.lang.Math;
Import java.util.File;
Import java.util.Writer;

public class guessingGame2 {
	public static void main(String[] arg) {

		Scanner scanner = new Scanner(System.in);
		PrinterWriter = PrinterWriter("Scores.txt");	
	
		Static String [] PlayersArray;
		static int []
    		// asking user for number
    		int rando = guessNumber - 1;
    		// number of tries it takes
		int numberOfTries = 0;
		// asking to play
		boolean play = true;
		// asking user if new
		int score = 100;
		boolean yn = true;
		
		int highestScore = 100;
		String highestName = "";

		int secondScore = 0;
		String secondName = "";
		
		Player[] playerList = new Player[25]; // up to 25 players can play
		playerCt = 0; // start of the game there are no players
		
		while (yn) {
		 System.out.println("Please enter your name");
		 userName = name.nextLine();
		 System.out.println("Are you a new player?");
		 System.out.println("Y/n);
		 decision = kbd.nextLine();
		 
		 switch(decision) {
		  case "yes":
		   yn = false;
		   break;
		  
		  case "no":
		   yn = true;
		   break;
		  
		  default:
		   System.out.println("please enter again");
		   return default;
		   break;

		 playerList[playerCt] = newPlayer; // putting new player in array.
		 System.out.println("Hello" + userName + "Welcome to the guessing game!");
		
    		// message to players about scoring system
    		
		System.out.println("The lower number of guesses the better your score!");
		
		while (play = true) {

			// Creating random number
			int guessNumber = rand.nextInt(15) + 1;
			System.out.println("The number I am thinking of is between 1 and 15, can you guess it");
			System.out.println("Enter your guess!");

   			 // checking for answer
			do {
    				// asking user for number
    				rando = consoleIn.nextInt();
				numberOfTries++
  

	      			// telling player answer too high
      				if (rando > 15) {
        					System.out.println("Your number is too high, the number is less than 15.");
		  			Score = Score - 1;
      				}
     				else if( guessNumber > rando ) {
           				System.out.println("Your number is too high! Try another guess! ");
       					Score = Score - 10;
       				}
				else if ( guessNumber < rando ) {
					System.out.println("Your number is too low! Try another guess!");
					Score = Score - 10;

	        			// telling them no negative numbers
        				else if( guessNumber  < 1   ) {
          				System.out.println(" The Number is not negative. Try a different number!  ");
					Score = Score - 1;
        				}
				else if ( rando == guessNumber ) {
					// telling user they got the correct answer with how many attempts
					Systemm.out.println("Congratulations " + userName + "it took you " + numberOfTries + "attempts to guess the answer");
       			}

		System.out.println("You win!");
		System.out.println("The number was " + guessNumber);
		System.out.println("It took you " + numberOfTries + "tries");
		System.out.println("Your score is " + Score);
		
		
		if (rando > highestScore) {
			secondScore = highestScore;
			secondName = highestName;

			highestScore = Score;
			highestName = userName;
		}
		else if ( rando > secondScore) {
			secondScore = Score;
			secondName = userName;
		}
		
		System.out.println("Cong

		// asking user if they want to play the game again
		System.out.println("Would you like to play again " + userName + " [Y/N]");
		playAgain = answer.nextLine();

		// if user says yes
		if (playAgain.equalsIgnoreCase("Y")) {
			play = true
			count 0;
			numberOfTries ++
		}
		// if user says no
		else if (play again.equalsIgnoreCase("N")) {
			play = false;
			System.out.println("Thanks for playing " + userName + "! Please come back soon!");
			writer.println(userName, // need score here
			break;
		}

 	 }
	}
}
