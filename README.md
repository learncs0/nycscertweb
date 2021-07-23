# nycscertweb

```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
## This page will highlight learning in 3 courses of the CS Certification Program
1. Programming in Java
2. Data Structrues
3. Methods I


### Course 1:  Programming in Java <br/>
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
    }
```

### Course 2: Data Structures <br/>
Maze program with Eric L, Michelle B  <br/>
Here is a screenshot of a portion of the code <br/>
![alt text](https://github.com/learncs0/nycscertweb/blob/main/Screen%20Shot%202021-07-22%20at%206.53.19%20PM.png)
 
 ### Course 3:  Methods I <br/>
 We learned how we could use NetLogo to introduce students to a new programming language <br/>
 [Here's a link to the NetLogo visualizations](https://ccl.northwestern.edu/netlogo/models/) 
