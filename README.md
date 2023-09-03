# swapno.

import java.util.Scanner;

public class Practice {
    public static void main(String[] args) {
        int num1, num2;
        System.out.println("Enter two numbers");
        Scanner sc = new Scanner(System.in);
        num1 = sc.nextInt();
        num2 = sc.nextInt();
        System.out.println("Before swapping no. first no. : " + num1 + "  second no. :" + num2);
        int temp = 0;
        temp = num1;
        num1 = num2;
        num2 = temp;
        System.out.println("After swapping no. first no. : " + num1 + "  second no. :" + num2);
        num1 = num1+num2;// 5+6 = 11
        num2 = num1-num2;//11-6 = 5
        num1 = (num1-num2);//11-5 = 6
        System.out.println("After swapping no. first no. : " + num1 + "  second no. :" + num2);
    }
}
