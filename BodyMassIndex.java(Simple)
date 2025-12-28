import java.util.Scanner;

public class BodyMassIndex {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        //A scanner is defined to get values from the user.

        System.out.println("Welcome to body mass index calculation.");
        System.out.print("Please enter your height in meters = ");
        double height = input.nextDouble();
        System.out.print("Please enter your weight in kilograms as a whole number = ");
        int kilogram = input.nextInt();
        //A welcome has been made for the user and some information has been requested.

        double account = kilogram/(height*height);
        //Body mass index has been calculated.

        if((18.5<account) && (account<24.9)) {
            System.out.print("You are at your ideal weight.");
        }else if (24.9<account) {
            System.out.print("You are above your ideal weight.");
        }else
            System.out.print("You are below your ideal weight.");
        /*The value entered by the user has been shown to
        the user on the console, indicating which scale it falls into.*/
    }
}
