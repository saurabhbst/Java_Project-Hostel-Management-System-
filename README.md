# Java_Project-Hostel-Management-System-
.import java.util.*;

public class Hostelmanagement {

    void menu()

    {

        System.out.println("Price for 1 seater with Ac is 100000");

        System.out.println("Price for 2 seater with Ac is 90000");

        System.out.println("Price for 4 seater with Ac is 80000");

        System.out.println("Price for 1 seater Non Ac is 70000 ");

        System.out.println("Price for 2 seater Non Ac is 60000");

        System.out.println("Price for 4 seater Non Ac is 50000");

        System.out.println("Price for Dormatory  is 40000");

    }

    public static void main(String[] args) {

        Scanner sc=new Scanner(System.in);

        Hostelmanagement ob1=new Hostelmanagement();

        System.out.println("Enter your id and password");

        System.out.println("Your id is :");

        int id=sc.nextInt();

        System.out.println("Your Pass is :");

        int pass=sc.nextInt();

        if(id == 12113853 && pass==12345)

        {

            ob1.menu();

        }

        else

            System.out.println("Invalid credentials");

    }

}
