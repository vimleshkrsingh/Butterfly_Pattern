# Butterfly_Pattern


public class ButterflyPattern
{
	public static void main(String[] args) {
		 int n=10;
		 //upper first half
		 for(int i=1; i<=n; i++)
		 {
		     for(int j=1; j<=i; j++)
		     {
		         System.out.print("*");
		     }
		     //spaces
		     int spaces= 2*(n-i);
		     for(int j=1; j<=spaces; j++)
		     {
		         System.out.print(" ");
		         
		     }
		     //upper second half
		     for(int j=1; j<=i; j++)
		     {
		         System.out.print("*");
		     }
		     System.out.println();
		 }
		 //lower first half
		 for(int i=n; i>=1; i--)
		 {
		     for(int j=1; j<=i; j++)
		     {
		         System.out.print("*");
		     }
		     //spaces
		     int spaces= 2*(n-i);
		     for(int j=1; j<=spaces; j++)
		     {
		         System.out.print(" ");
		         
		     }
		     //lower second half
		     for(int j=1; j<=i; j++)
		     {
		         System.out.print("*");
		     }
		     System.out.println();
		 }
	}
}
