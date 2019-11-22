# arthimeticoperation
import java.util.*;
class arithmeticoperation
{
    public static void main(String args[])throws Exception
    {
       Scanner sc= new Scanner(System.in);
       int n,a,b,c;
       
       System.out.println("enter your choice:- 1 for addition, 2 for subtraction, 3 for multiplication, 4 for division");
       n=sc.nextInt();
       System.out.println("enter 2 numbers");
       a=sc.nextInt();
       b=sc.nextInt();
       switch(n)
       {
           case 1:
           {
           c=a+b;
           System.out.println("addition is"+c);
           break;
            }
          case 2:
           {
           if(a>b)
           { 
               c=a-b;
            }
            else
            {
                c=b-a;
            }
           System.out.println("subtraction is"+c);
           break;
            }
             case 3:
           {
           c=a*b;
           System.out.println("multiplication is"+c);
           break;
           }
           case 4:
           {
           c=a/b;
           System.out.println("division is"+c);
           break;
           }
           default:
           {
           System.out.println("wrong choice");
            }
        }
    }
}

        
       
