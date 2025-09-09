Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.





ANSWERS

1. The class diagram consists of only classes and their source code components.
   The object diagram consists of created objects on the object bench.

2. You can change a class diagram by adding or removing a class or 2 classes reliant on one another.

3. You can change an object diagram by adding or removing an object, but if you remove the object, it will still exist in the running project and be out of the list.

4. private String tutor;

6. I should call the method getValue or check the inspector on the minutes object to see if it has rolled over. If it has rolled over, then I should increment once on hours.

8. Yes, both calls to setValue resulted in a change to the stored value. When setting a value lower than the limit, it will keep the chosen value. Setting a value higher than the limit will cause it to roll over the limit and reset the value back to 0 discarding the rest of the set value over the limit.

13. 0

14. All the values over the limit are now valid.

15. ! false
    (34 != 33) && ! false 

16. if((a > 1) && (b > 1)) {
    value = true;
    }
   else {
    value = true;
    }

17.  

18. The 3 digit value is returned normally.
