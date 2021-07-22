# nycscertweb
 ## This page will highlight learning in the CS Certification Course and 
 
 ### 1.  Programming in Java with Benson Chaouiki Dwayne & Lyuba <br/>
    #### code from Nim that I understand <br/>
                public class Nim{ <br/>
                  public static void main(String[] args){ <br/>
            //create variable to store the number of stones <br/>
            int stonesRemoved = 0; <br/>
            //create variable for current number of stones <br/>
            int stonesRemain = 12; <br/>
            while (stonesRemain > 0){ <br/>
              boolean valid = false; <br/>
              while (!valid){ <br/>
              //ask user for number of stones 1-3 out of 12 stones total <br/>
              System.out.println("There are " + stonesRemain + " stones, please choose between 1-3"); <br/>
              //create a scanner class <br/>
              Scanner in = new Scanner(System.in); <br/>
              //read in stones (nextIn-stones rem) <br/>
              stonesRemoved = in.nextInt(); <br/>
              //check if input until it is valid - use loop <br/>
              valid = checkValid(stonesRemain, stonesRemoved); <br/>
              if(!valid) <br/>
              { <br/>
                System.out.println("Invalid entry."); <br/>
              } <br/>
            } <br/>

 Data Structures <br/>
 
 
 Methods I <br/>
