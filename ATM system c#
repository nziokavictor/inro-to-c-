using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine("===================");
        Console.WriteLine("    ATM MENU    ");
        Console.WriteLine("===================");
        Console.WriteLine("1. Check Balance");
        Console.WriteLine("2. Withdraw Cash");
        Console.WriteLine("3. Deposit Money");
        Console.WriteLine("4. Transfer Funds");
        Console.WriteLine("5. Change PIN");
        Console.WriteLine("6. Exit");
        Console.WriteLine("7. Mini Statement");
        Console.WriteLine("===================");

        Console.Write("Enter option: ");
        int option = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine("You selected " + option);

        switch (option)
        {
            case 1:
                Console.WriteLine("Your balance is KES 10,000.");
                break;

            case 2:
                Console.Write("Enter amount to withdraw: ");
                int withdrawAmount = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("Withdrawal of KES " + withdrawAmount + " successful.");
                break;

            case 3:
                Console.Write("Enter amount to deposit: ");
                int depositAmount = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("Deposit of KES " + depositAmount + " successful.");
                break;

            case 4:
                Console.Write("Enter amount to transfer: ");
                int transferAmount = Convert.ToInt32(Console.ReadLine());
                Console.WriteLine("Transfer of KES " + transferAmount + " successful.");
                break;

            case 5:
                Console.Write("Enter new PIN: ");
                string newPin = Console.ReadLine();
                Console.WriteLine("PIN changed successfully.");
                break;

            case 6:
                Console.WriteLine("Thank you for using the ATM.");
                break;

            case 7:
                Console.WriteLine("Displaying your last 5 transactions...");
                break;

            default:
                Console.WriteLine("Invalid menu option.");
                break;
        }
    }
}
