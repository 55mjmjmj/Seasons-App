import java.util.Scanner;
public class SeasonAppA3
{
		public static void main (String [] args)
			{
				Scanner scan=new Scanner(System.in);
				System.out.println("Enter the month");
				int month=scan.nextInt();
				switch (month)
				{
					case 12,1,2 : System.out.println("The month number "+month+" corresponds to winter.");
					break;
					case 3,4,5 : System.out.println("The month number "+month+" corresponds to spring.");
					break;
					case 6,7,8 : System.out.println("The month number "+month+" corresponds to summer.");
					break;
					case 9,10,11 : System.out.println("The month number "+month+" corresponds to fall.");
					break;
					default: System.out.println("The month number "+month+" corresponds to Invalid month.");
				}
			}
}
