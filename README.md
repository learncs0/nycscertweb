# nycscertweb
 ## This page will highlight learning in the CS Certification Course
 

 1.  Couurse 1:  Programming in Java <br/>
 Nim program with with Benson Chaouiki Dwayne & Lyuba  <br/>
                
                 ```javascript
                 import java.io.*;
import java.util.*;
import java.util.Scanner; //not necessary
public class Nim{
  public static void main(String[] args){
    //create variable to store the number of stones
    int stonesRemoved = 0;
    //create variable for current number of stones
    int stonesRemain = 12;
    while (stonesRemain > 0){
      boolean valid = false;
      while (!valid){
      //ask user for number of stones 1-3 out of 12 stones total
      System.out.println("There are " + stonesRemain + " stones, please choose between 1-3");
      //create a scanner class
      Scanner in = new Scanner(System.in);
      //read in stones (nextIn-stones rem)
      stonesRemoved = in.nextInt();
      //check if input until it is valid - use loop
      valid = checkValid(stonesRemain, stonesRemoved);
      if(!valid)
      {
        System.out.println("Invalid entry.");
      }
    }```
            

 Data Structures <br/>
 
 
 Methods I <br/>
