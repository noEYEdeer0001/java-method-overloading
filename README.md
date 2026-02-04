import java.util.Scanner;
class sameer
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int a=sc.nextInt(); // taking inputs
        int b=sc.nextInt(); // taking inputs
        int c=sc.nextInt(); // taking inputs
        A obj = new A();
        obj.sxm(a,b); // calling method 1
        obj.sxm(a,b,c); // calling method 2
    }
}
class A
{
    public void sxm(int a , int b)
    {
        System.out.println("sum of a and b: "+ a+b);
    }
    public void sxm(int a, int b, int c) // method overloading here
    {
        System.out.println("sum of a , b and c: "+ a+b+c);
    }
}
