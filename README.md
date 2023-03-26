# leap
//{ Driver Code Starts
//Initial Template for Java

import java.util.Scanner;

class Main {

    
// } Driver Code Ends
//User function Template for Java

public static void utility(int y){
    String isLeap = "False";

    

public static void utility(int y){
    String isLeap = "False";
    if( y %  400 == 0 ){
        isLeap="True";
        
    }
    if( y %  4 == 0 && y %  100 != 0 ){
        isLeap="True";
        
    }
   
    System.out.println(isLeap);
}
    
    System.out.println(isLeap);
}



    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        int t = scn.nextInt();
        while(t-- > 0) {
            int y = scn.nextInt();
            utility(y);
        }
        scn.close();
    }
}

