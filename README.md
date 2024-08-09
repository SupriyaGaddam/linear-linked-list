# linear-linked-list
# linear-linked-list
import java.util.Scanner;
public class Main{
  public static void main(String[] args)
  {
    int found=0;
    Scanner sc=new Scanner(System.in);
    System.out.println("enter array size");
    int n=sc.nextInt();
   
    for(int i=0;i<n;i++)
    {
      a[i]=sc.nextInt();
    }
    System.out.println("enter the element you find");
    
    int item=sc.nextInt();
    
    for(int i=0;i<a.length;i++)
    {
      if(a[i]==item);
    }
    
    if(found==0)
    System.out.println("element not found");
    else
    System.out.println("element found");
  }
}
