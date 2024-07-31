# swap-of-2-numbers
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int n= sc.nextInt();
        int m=sc.nextInt();
        System.out.println("n: "+n+",m: "+m);
        int c=n;
        n=m;
        m=c;
        System.out.println("n: "+n+",m: "+m);
    }
}
