package clark;
import java.Util.Scanner;



public class clark{


	pubclic static void main (String []args){



	Scanner scan = new Scanner(System.in);

String name,id,prog;
int units;
double tfee=745.00;
double mis=7519.00;
double ttltuton,ttlam;
double pay1,pay2,pay3;


System.out.println("Name :");
name = scan.nextLine();
System.out.println("ID Number :");
id = scan.nextLine();
System.out.println("Program :");
prog = scan.nextLine();
System.out.println("Units Enrolled :");
units = scan.nextInt();

ttltuton = units * tfee;
ttlam = ttltuton + mis;
pay1 = ttlam*.90;
pay2 = 10000-(ttlam/2);
pay3 = 5000-(ttlam/2);

System.out.println("total tuition fee:"+ttltuton);
System.out.println("total ammount :"+ttlam);
System.out.printf("\n pay option1 %.2f ",pay1);
System.out.printf("\n pay option2 %.2f ",pay2);
System.out.printf("\n pay option3 %.2f ",pay3);
System.out.println("\n END");













}
yowww
	






}
