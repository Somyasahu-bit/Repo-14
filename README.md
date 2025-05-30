# Repo-14
Switch Statement//  Switch Statement
import java.util.Scanner;
class Switch {
    public static void main(String[] args) {
    int a=10,b=20,ch;
    System.out.println("Enter user choice..!");
    Scanner r=new Scanner(System.in);
    ch=r.nextInt();
    switch(ch)
    {
     case 1:
         System.out.println("Sum " + (a+b));
     break;
     case 2:System.out.println("Sub " + (a-b));
     break;
     case 3:System.out.println("Multi " + (a*b));
     break;
     case 4:System.out.println("Div " + (a/b));
     break;
     default:System.out.println("Invalid choice");
    }
    }
}

