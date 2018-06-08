
# JAVA PROGRAMS

# 1  PROGRAM TO PRINT MATRIX MAXIMUM COLUMN SUM

import java.util.*;
class Hello {

    public static void main(String[] args) {
Scanner s=new Scanner(System.in);
int n,sum=0,max=0;
 n=s.nextInt();   
 int a[][]=new int[n][n];
for(int i=0;i<n;i++)
for(int j=0;j<n;j++)
a[i][j]=s.nextInt();
for(int j=0;j<n;j++)
{
    sum=0;

    for(int i=0;i<n;i++)
    {
    sum+=a[i][j];
    }
     if(sum>max)max=sum;          
 }
 System.out.print(max);       
}
}


# 2  PROGRAM TO PRINT THE CHARACTERS IN THE EVEN PLACES OF A STRING IN REVERSE ORDER

import java.util.*;
class Even
{
public static void main(String[]args)
{
	Scanner s=new Scanner(System.in);
	String s1=s.nextLine();
	char[]a=s1.toCharArray();
	String t="";
	for(int i=0;i<a.length;i++)
	{
		if(i%2!=0)
		{
			t=t+a[i];
		}
	}
System.out.println(t);
StringBuffer sb=new StringBuffer(t);
sb.reverse();
System.out.println(sb);

	}	
}
