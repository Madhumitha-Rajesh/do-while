# do-while

package pkgdo.pkgwhile;

import java.util.Scanner;
public class DoWhile {

    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc=new Scanner(System.in);
        int num;
        System.out.print("enter the number:");
        num=sc.nextInt();
        int i=1;
        do{
            System.out.println(i);
            i++;
        }while(i<=num);

    }
    
}


Output- 

enter the number:10
1
2
3
4
5
6
7
8
9
10
