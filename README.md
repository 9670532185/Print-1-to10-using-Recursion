# Print-1-to10-using-Recursion
//progtam to print 1 to 10
public class Recursion {
    public static void print(int n)
    {
//base case
if(n==11)
{
return ;
}
System.out.println(n);
print(n+1);
     
    
    }
    public static void main(String[] args)
    {
    int n=1;
    print(n);
  
    }
    
}
