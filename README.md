## ACTIVITY

## Program_1


import java.io.*;
import java.util.*;
import java.util.Scanner;

public class code1 {

    public static void main(String[] arg) {

        Scanner sc = new Scanner(System.in);
        System.out.println("Enter first name: ");
        String A = sc.next();
        System.out.println("Enter last name: ");
        String B = sc.next();

        int len_C = A.length();
        int len_D = B.length();
        System.out.println((("Output: " + A.substring(0, 1)).toUpperCase() + (A.substring(1, len_C).toLowerCase()))
                + " " + ((B.toUpperCase())));
    }
}