### Reading 8, what did I learn and what should you know? 
* JavaScript contains operators. It is not alone in this, these operators are common across many programming languages
* A **few** of these operators are: ```==``` equal to, ```>,<``` Greater than and Less than, ```!=``` not equal to. 
 * these are only a few of the many different operators. A new one to me was the ```===``` or strictly equal to, This requires both items being compared to be the same. So 6 and '6' would not be equal. 
 * JavaScript also has logic operators which are similiar to what I have talked about before. The AND, OR, and NOT. 
  * These JavaScript ones are called Logical AND, ```&&```, Logical OR, ```| |```, and Logical NOT, ```!```. 
   * ```&&``` will return true if both inputs are true. ```| |``` will return true if 1 input is true and false if both are false. ```!``` will return true if it would be false if it didn't have the ```!```.  ```! false``` will return ```True```


   ### Loops. What are they? What do they do?

Loops are something I consider to be the bread and butter of a program. 
* Loops like operators are common across many programming languages.
* JavaScript has a few and some common ones are
 * The ```For``` loop
  * The ```For``` loop is used to run code a set amount of times. 
 * The ```While``` loop
  * The ```While``` loop is used when you do not know when the code should stop running. You could set the code to True and it would run forever
 * The ```Do While``` loop 
  * The ```Do While``` loop is like the ```While``` loop but will always run the code inside of it at least once. 

  A rough example of a while loop could be:  
``` var counter = 1;```
   ``` while (counter <= 10) {```
     ```   console.log(counter);```
      ```  counter +=1;```
    ```}```