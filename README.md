import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s=new Scanner(System.in);
        int row = s.nextInt();
        for (int i = 1; i <= row ; i++) {
        for (int j = 1; j <= row - i; j++) {
        System.out.print(" ");
        }
        for (int k = 1; k <= i; k++) {
        System.out.print("*");
        }
        System.out.println("");
        }
    }
}
