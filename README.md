# Sandwichshop
import static java.lang.System.out;
import java.util.Scanner;


public class SandwichShop {

    public static void main(String[] args) {

        // Don't change these lines.
        Scanner keyboard = new Scanner(System.in);
        int goalForVeggies = 50;
        int goalForBurgers = 250;
        int goalForSubs = 180;
        int goalForSoup = 70;

        out.println("Checking sales goasl.");
        out.println("The sales goal for veggie sandwich is" + goalForVeggies);
        out.println("How many veggie sandwiches were sold today?");
        int veggiesSold = keyboard.nextInt();

        if (veggiesSold < goalForVeggies) {
            out.println("Fell short.");
        } else {
            out.println("Made goal for veggies!");
            keyboard.skip("\n");
        }

        out.println("The sales goal for burgers is " + goalForBurgers);
        out.println("How many burgers were sold today?");
        int burgersSold = keyboard.nextInt();

        if (burgersSold < goalForBurgers) {
            out.println("Fell short.");
        } else {
            out.println("Made goal for burgers!");
            keyboard.skip("\n");
        }

        out.println("The sales goals for subs is" +goalForSubs);
        out.println("How many subs were sold today?");
        int subsSold= keyboard.nextInt();

        if (subsSold < goalForSubs) {
            out.println("Fell short.");
        } else {
            out.println("Made goal for subs");
            keyboard.skip("\n");
        }

        out.println("The sales goal for soup is" +goalForSoup);
        out.println("How many bowls of soup were sold today?");
        int soupSold= keyboard.nextInt();

        if (soupSold < goalForSoup) {
            out.println("Fell short.");
        } else {
            out.println("Made goal for soup!");
            keyboard.skip("\n");
        }


    }
}
