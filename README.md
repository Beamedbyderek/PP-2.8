# PP-2.8


/* 

10/2/2022

 Derek Durand

Converts time to seconds

*/ 

import java.util.Scanner;


public class PP28 {

    
    public static void main(String[] args) {
        
            Scanner sc = new Scanner(System.in);
            
            System.out.print("Enter hour amount:");      
            float hourAmount = sc.nextFloat();
            
            System.out.print("Enter minute amount:");    // compiles information
            float minuteAmount = sc.nextFloat(); 
            
            System.out.print("Enter second amount:");
            float secondsAmount = sc.nextFloat();
            
            float hoursToSeconds = (float) (hourAmount*3600);         
            float minutesToSeconds = (float) (minuteAmount*60);     
             
            float totalSeconds = (float) (minutesToSeconds + hoursToSeconds + secondsAmount); // calculations
            
            System.out.println("Your total amount of seconds is " + totalSeconds);
       
    }
    
}
