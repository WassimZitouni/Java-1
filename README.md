import java.util.Scanner;

public class java4parta
 {
    // ask the user
    public static void main(String[] args) 
    {
        Scanner scanner = new Scanner(System.in);
       
        String movieTitle = askForMovieTitle(scanner); 
        printMovieTitle(movieTitle);
        scanner.close(); 
    }
    // ask for the movie title
    public static String askForMovieTitle(Scanner scanner)
     {
        System.out.println("Please enter your favorite movie:");
        return scanner.nextLine();
    }
    public static void printMovieTitle(String movieTitle) {
        System.out.println("Your favorite movie is " + movieTitle);
    }
}
