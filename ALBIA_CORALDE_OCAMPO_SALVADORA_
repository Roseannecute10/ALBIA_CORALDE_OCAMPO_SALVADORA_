import java.util.Scanner;

public class clock {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        boolean continueConversion = true;

        // Initial message to the user
        // Loop to allow multiple conversions until the user opts out
        while (continueConversion) {
            
            // Display the options
            System.out.println("[1] Convert Seconds to Minutes");
            System.out.println("[2] Convert Seconds to Hours");
            System.out.println("[3] Convert Minutes to Seconds");
            System.out.println("[4] Convert Minutes to Hours");
            System.out.println("[5] Convert Hours to Seconds");
            System.out.println("[6] Convert Hours to Minutes");
            System.out.print("Choose the Conversion: ");
            
            // Get user's choice
            int choice = scanner.nextInt();
            double value, result = 0;

            // Perform conversion based on user's choice
            switch (choice) {
                //Convert Seconds to Minutes
                case 1:
                    System.out.print("Enter the Value: ");
                    value = scanner.nextDouble();
                    result = value / 60.0;
                    System.out.println("Seconds to Minutes: " + result);
                    break;

                //Convert Seconds to Hours
                case 2:
                    System.out.print("Enter the Value: ");
                    value = scanner.nextDouble();
                    result = value / 3600.0;
                    System.out.println("Seconds to Hours: " + result);
                    break;

                //Convert Minutes to Seconds
                case 3:
                    System.out.print("Enter the Value: ");
                    value = scanner.nextDouble();
                    result = value * 60.0;
                    System.out.println("Minutes to Seconds: " + result);
                    break;

                //Convert Minutes to Hours
                case 4:
                    System.out.print("Enter the Value: ");
                    value = scanner.nextDouble();
                    result = value / 60.0;
                    System.out.println("Minutes to Hours: " + result);
                    break;

                //Convert Hours to Seconds
                case 5:
                    System.out.print("Enter the Value: ");
                    value = scanner.nextDouble();
                    result = value * 3600.0;
                    System.out.println("Hours to Seconds: " + result);
                    break;

                //Convert Hours to Minutes
                case 6:
                    System.out.print("Enter the Value: ");
                    value = scanner.nextDouble();
                    result = value * 60.0;
                    System.out.println("Hours to Minutes: " + result);
                    break;

                default:
                    System.out.println("Invalid option.");
            }

            // Ask if the user wants to perform conversion again
            System.out.print("Do you want to convert time2? (Y/N): ");
            char response = scanner.next().toUpperCase().charAt(0);
            if (response != 'Y') {
                continueConversion = false;
                System.out.println("Thank you!");
            }
        }

        // Close program
        scanner.close();
    }
}
