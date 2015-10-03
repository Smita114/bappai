# bappai
public class porta1
{
    
   public static void main()
   {
       for(int i = 5; i>=1;i--)
       {
           for (int j = 5 ; j>=i ;j--)
           {
               System.out.print(j +" ");
            }
            
            
        for(int j = 1; j <=(i + i); j++)
           {
               System.out.print("  ");
            }
            for(int k = 5 ; k>=i; k--)
            {
                System.out.print(k+ " ");
            }
        System.out.println(" ");
      }
    }
  }
