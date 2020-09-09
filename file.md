# Question 2 : Explain range in python with various examples

Answer : The range function returns a sequence of numbers, starting from a number,  and  
 increments by 1 (by default) or any other specified value, and stops before a specified number.  
  
Syntax : *range(start, stop, step)*   

*start* : An integer number specifying at which position to start.  
*stop* : An integer number specifying at which position to stop. The range doesn't include this  
                 number in the result. It stops just before this value.  
 *step* : An integer number specifying the incrementation or decrementation.  
  
Here, *start* and *step* are optional. If they are not specified, 0 is taken as the default  
value for *start* and 1 is taken as the default value for *step* .  
  
*range()* only works with the integers. All arguments must be integers. We can not use float  
number or any other type in a *start, stop* and *step* argument. Also, The *step* value must not be  
zero. If *step* is zero Python raises a ValueError exception.  
  
Some Examples :  
  
1. Printing first 5 whole numbers using range function
*for i in range(5) :*  
	*print(i)*  
  
Output :  
0  
1  
2  
3  
4   
  
2. Printing a sequence of numbers from 3 to 5  
*for i in range(3, 6) :*  
	*print(i)*  
  
Output :   
3  
4  
5  
  
3. Printing a sequence of numbers from 3 to 19, but increment by 2 instead of 1  
*for n in range(3, 20, 2):*  
  *print(n)*  
  
Output:  
3  
5  
7  
9  
11  
13  
15  
17  
19  
  
  
# Question 3 : What will be the result of  *int(6.6) + int(4.9)*  
  
Answer : 10

