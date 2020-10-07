//Q.1
class Polygon
{
public static void main(String [] args)
{
Scanner sc1=new Scanner(System.in);
System.out.println("enter the first element");
double n1=sc1.nextDouble();
System.out.println("enter the second element");
double n2=sc1.nextDouble();
double arr[][]=new double[n1][n2];
for(int i=0;i<arr.length;i++)
{
system.out.println("Enter first "+i+" elements:");
for(int j=0;j<arr[i].length;j++)
{
System.out.println("enter second "+j+" elements");
arr[i][j]=sc1.nextDouble();
}
}
System.out.println("elements are:");
for(int i=0;i<arr.length;i++)
{
n1[i]=-arr.n1[i];
for(int j=0;j<arr.length;j++)
{
n2[i]=-arr.n2[i];
System.out,println(arr[i][j]+" ");
}
}
for(int i=0;i<arr.length;i++)
{
if(int n1[i]==arr[i] && n2[i]==arr[i])
{
System.out.println(true);
}
else
{
System.out.println(false);
}
}
}
}



//Q.2
class Building
{
public static void main(String [] args)
{
Scanner sc1=new Scanner(System.in);
System.out.println("enter the buildings");
double n=sc1.nextDouble();
System.out.println("enter the sources");
double s=sc1.nextDouble();
double arr[][]=new double[n][s];
int result;
for(int i=0;i<arr.length;i++);
{
System.out.println(""Enter "+i+" buildings");
for(int j=0;j<arr[i].lenrth;j++)
{
ar[i][j]=sc1.nextDouble();
}
}
System.out.println("Elements are:")
for(int i=0;i<arr.length;i++);
{
for(int j=0;j<arr[i].lenrth;j++)
{
System.out.println(arr[i][j]+" ")
}
}
for(int i=1;i<n;i++)
{
result=n*4*2;
System.out.println("output is: "+result);
}
}
}


