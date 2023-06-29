# prep5  // number pattern printing in java 


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	for (int i=1;i<=n;i++)
	{
		for (int k=1;k<=i;k++)
		{
			System.out.print(k+" ");
		}
	  System.out.println();
     }
	}
}

enter no of rows
5
1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5 


package my_first_java_Project;
import java.util.Scanner;

public class main {

	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	System.out.println("enter no of rows");
	int  n=sc.nextInt();
	int j=1;
	for (int i=1;i<=n;i++)
	{
		for (int k=1;k<=i;k++)
		{
			System.out.print(j++ +" ");
		}
	  System.out.println();
     }
	}
}

enter no of rows
6
1 
2 3 
4 5 6 
7 8 9 10 
11 12 13 14 15 
16 17 18 19 20 21 


package my_first_java_Project;

import java.util.Scanner;

public class Pascal {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
         System.out.println("entere the no of rows");
         Scanner sc=new Scanner(System.in);
         int n=sc.nextInt();
         int number=1;
         for(int i=0;i<=n;i++)
         {
        	 for (int k=0;k<=(n-i);k++)
        	 {
        		 System.out.print(" ");
        	 }
        	 number=1;
        	 for(int j=0;j<=i;j++) {
        		 System.out.print(number+ " ");
        		 number=number*(i-j)/(j+1);
        		 
        	 }
        	 System.out.println();
         }
	}

}
entere the no of rows
4
     1 
    1 1 
   1 2 1 
  1 3 3 1 
 1 4 6 4 1 

package my_first_java_Project;

import java.util.Scanner;

public class diamond {

	public static void main(String[] args) {
		 Scanner sc=new Scanner(System.in);
		 System.out.println("enter the no of rows");
		 int n=sc.nextInt();
		 for (int i=1;i<=n;i++)
		 {
			 for(int k=1;k<=n-i;k++)
			 {
				 System.out.print(" ");
			 }
			 for(int j=i;j>=1;j--)
             {
				 System.out.print(j);
             }
			 for (int y=2;y<=i;y++)
			 {
				 System.out.print(y);
			 }
				 
				System.out.println();	
		}for (int i=n-1;i>=1;i--)
		 {
			 for(int k=1;k<=n-i;k++)
			 {
				 System.out.print(" ");
			 }
			 for(int j=i;j>=1;j--)
            {
				 System.out.print(j);
            }
			 for (int y=2;y<=i;y++)
			 {
				 System.out.print(y);
			 }
				 
				System.out.println();	
		}
		 
		// TODO Auto-generated method stub
	}
}

enter the no of rows
5
    1
   212
  32123
 4321234
543212345
 4321234
  32123
   212
    1

package my_first_java_Project;

import java.util.Scanner;

public class Lefttriangle {

	public static void main(String[] args) {
		 Scanner sc=new Scanner(System.in);
		 System.out.println("enter the no of rows");
		 int n=sc.nextInt();
		 for (int i=0;i<=n;i++)
		 {
			 for(int k=1;k<=i;k++)
			 {
				 System.out.print(i);
			 }
			 System.out.println();	// TODO Auto-generated method stub

	}
	}

}

enter the no of rows
9

1
22
333
4444
55555
666666
7777777
88888888
999999999

package my_first_java_Project;

import java.util.Scanner;

public class Lefttriangle {

	public static void main(String[] args) {
		 Scanner sc=new Scanner(System.in);
		 System.out.println("enter the no of rows");
		 int n=sc.nextInt();
		 for (int i=n;i>=1;i--)
		 {
			 for(int k=n;k>=i;k--)
			 {
				 System.out.print(k);
			 }
			 System.out.println();	// TODO Auto-generated method stub

		 }
	}

}

enter the no of rows
6
6
65
654
6543
65432
654321

package my_first_java_Project;

import java.util.Scanner;

public class Lefttriangle {

	public static void main(String[] args) {
		 Scanner sc=new Scanner(System.in);
		 System.out.println("enter the no of rows");
		 int n=sc.nextInt();
		 for (int i=1;i<=n;i++)
		 {
			 int num;
			 if(i%2==0)
			 {
				num=0;
				for(int k=1;k<=n;k++)
				{
					System.out.print(num);
					num=(num==0)?1:0;
				}
			 }
			 else
			 {
			 num=1;
			 for(int k=1;k<n+1;k++)
			 {
				 System.out.print(num);
				 num=(num==0)?1:0;
			 }
			 }
			 System.out.println();
		 }//TODO Auto-generated method stub
	  
	}

}

enter the no of rows
9
101010101
010101010
101010101
010101010
101010101
010101010
101010101
010101010
101010101

package my_first_java_Project;

import java.util.Scanner;

public class Lefttriangle {

	public static void main(String[] args) {
		 Scanner sc=new Scanner(System.in);
		 System.out.println("enter the no of rows");
		 int n=sc.nextInt();
		 for (int i=1;i<=n;i++)
		 {
				for(int k=1;k<=i;k++)
				{
					if(k%2==0)
					{
						System.out.print(0);
					}
					else
					{
						System.out.print(1);
					}
				}
						
					System.out.println();
				}
			 }
	}


 enter the no of rows
8
1
10
101
1010
10101
101010
1010101
10101010
 



