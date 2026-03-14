public class Main {
    public static void main(String[] args) {

        int n = 5;

        for (int i = 1; i <= n; i++) {

            
            for (int s = 1; s <= n - i; s++) {
                System.out.print("  ");
            }

            
            for (int j = 1; j <= i; j++) {
                System.out.print(j + " ");
            }

        
            for (int k = i - 1; k >= 1; k--) {
                System.out.print(k + " ");
            }

            System.out.println();
        }
    }
}# java-test-0002-final-15968-nisha
Final Project Assignment - This repository contains the complete final project code and documentation.
