import java.util.Scanner;

public class Main {
  public static void main(String[] args){
    Scanner scanner = new Scanner(System.in); //scaner object
    int menuSelection; //variable to keep track of users current menu choice
    do { // do-while loop
      System.out.println("Choose an option, please!");
		  System.out.println("1. Cups to ounces");
		  System.out.println("2. Feet to meters");
		  System.out.println("3. Miles to yards");
		  System.out.println("4. Quit");

      menuSelection = scanner.nextInt();

      switch(menuSelection) {

      case 1:
    	  double cToP;
    	  System.out.println("Enter a quantity you would like to convert");
    	  cToP = scanner.nextDouble();
    	  double cToP2 = cToP * 8;
    	  System.out.println(cToP + " cups converts to " + cToP2 + " ounces");
      
      break;
      
      case 2: 
    	  double fToM;
    	  System.out.println("Enter a quantity you would like to convert");
    	  fToM = scanner.nextDouble();
    	  double fToM2 = fToM / 3.281;
    	  System.out.println(fToM + " feet converts to " + fToM2 + "meters");
    	  
      break;
    
      case 3:
    	  double mToY;
    	  System.out.println("Enter a quantity you would like to convert");
    	  mToY = scanner.nextDouble();
    	  double mToY2 = mToY * 1760;
    	  System.out.println(mToY + " miles converts to " + mToY2 + " yards");
    	  
       }
    
    }
    while (menuSelection != 4); //loop will continue until user chooses 4
    System.out.println("Thank you for playing!");

    scanner.close();

  }
}
