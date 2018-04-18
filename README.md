# Mathematics
## Algorithm to calculate Arithmetic and Geometric Progression
below is a example of a algorithm to calculate aritmtic and geometric progression.

 #include <iostream>
	

	using namespace std;
	

	int main(){
	  int a, sum, geo = 1;
	  cout << "Number";
	  cin >> a;
	  
	  
	  for (int i=1; i <= 10; i++){
	    sum += a;
	    geo *= a;
	    cout << "Iteration: " << i << endl;
	    cout << "Airthmetic: " << sum  << endl;
	    cout << "Geometric: " << geo << endl;
	    cout << endl;
	  }
	  return 0;
	}


## What is the probability of a random integer being divisible by 5?
the possability of a radnom integer being divisable by 5 is highly likey or in a more spesificsense it would be and 1/5 chance. This is becuase every number that ends with a 5 or a 0 such as 5, 10, 15, 20 and 25 etc. are multibles of 5 adn this would allow them to be devided by 5. This means that every number that ends with a 5 or a 0 is divisable by 5 and becuase there is a gap of 5 numbers before each multible of 5 such as 1, 2, 3, 4, (5), 6 ,7 ,8 ,9 (10) etc, it would be a 1/5 chance that a random integer would be divisible by 5.

## How to calculate the greatest common divisor and least common multiple of a given pair of numbers?
### LCM
The least common multiple, or LCM, is another number that's useful in solving many math problems. Let's find the LCM of 30 and 45. One way to find the least common multiple of two numbers is to first list the prime factors of each number.

30 = 2 × 3 × 5
45 = 3 × 3 × 5

Then multiply each factor the greatest number of times it occurs in either number. If the same factor occurs more than once in both numbers, you multiply the factor the greatest number of times it occurs.

2: one occurrence 
3: two occurrences 
5: one occurrence 
2 × 3 × 3 × 5 = 90 <— LCM

After you've calculated a least common multiple, always check to be sure your answer can be divided evenly by both numbers.

### GCD

GCD stands for Greatest Common Divisor. GCD is largest number that divides the given numbers.

GCD Example
Find the GCD of 45 and 54.

Step 1: Find the divisiors of given numbers:

The divisiors of 45 are : 1, 3, 5, 9, 15, 45

The divisiors of 54 are : 1, 2, 3, 6, 9, 18, 27, 54

Step 2: Find the greatest number that these two lists share in common. In this example the GCD is 9.

## Deduce the conditional probability of different events occurring within independent trials

below is a example of the the of how to Deduce the conditional probability of different events occurring within independent trials involving a dice throw.

A fair die is rolled.

Find the probability that the number rolled is a five, given that it is odd.
Find the probability that the number rolled is odd, given that it is a five.
Solution:

The sample space for this experiment is the set S={1,2,3,4,5,6}S={1,2,3,4,5,6} consisting of six equally likely outcomes. Let F denote the event “a five is rolled” and let O denote the event “an odd number is rolled,” so that

F={5} and O={1,3,5}
F={5} and O={1,3,5}
This is the introductory example, so we already know that the answer is 1/3. To use the formula in the definition to confirm this we must replace A in the formula (the event whose likelihood we seek to estimate) by F and replace B (the event we know for certain has occurred) by O:

P(F|O)=P(F∩O)P(O)
P(F|O)=P(F∩O)P(O)
Since F∩O={5}∩{1,3,5}={5}F∩O={5}∩{1,3,5}={5}, P(F∩O)=1∕6.P(F∩O)=1∕6.

Since O={1,3,5}O={1,3,5}, P(O)=3∕6.P(O)=3∕6.

Thus

P(F|O)=P(F∩O)P(O)=1∕63∕6=13
P(F|O)=P(F∩O)P(O)=1∕63∕6=13
This is the same problem, but with the roles of F and O reversed. Since we are given that the number that was rolled is five, which is odd, the probability in question must be 1. To apply the formula to this case we must now replace A (the event whose likelihood we seek to estimate) by O and B (the event we know for certain has occurred) by F:

P(O|F)=P(O∩F)P(F)
P(O|F)=P(O∩F)P(F)
Obviously P(F)=1∕6.P(F)=1∕6. In part (a) we found that P(F∩O)=1∕6.P(F∩O)=1∕6. Thus

P(O|F)=P(O∩F)P(F)=1∕61∕6=1

### the expectation of an event occurring from a discrete, random variable.

Uniformly random selection is only possible from a finite set; so this is what we do: we always select from a finite set but do this repeatedly, each time selecting from a bigger set. Here's a more accurate definition:

Let q be a Boolean function (i.e., a function that takes values true and false) defined on the set N of integers and q(n) the number of integers k∈Nn={a: 1≤a≤n} for which q(k)=true. We think of  q(n)n as the probability of an integer from Nn to have the property q.
Now, the probability that a random integer has property q is defined as  limn→∞q(n)n.
Let's see how this definition works for the problem of divisibility by 5.

Let n=5m+r, where 0≤r≤4}. The number q(n) of integers not exceeding n and divisible by 5 equals q(n)=⌊q(n)5⌋=m, where ⌊a⌋ is the floor function. Further,

q(n)n=mn=(n−r)/5n=15−r5n,

implying that indeed, limn→∞q(n)n=15.

### Identify simple shapes using co-ordinate geometry
below are two images which have example of how to Identify simple shapes using co-ordinate geometry. Co-ordinate geometry is the rules by which different shapes can be created and identified. for example, an equallateral triangle must have 3 sides of the same length and 3 equal angles. By following these rules, you will always end up with an equallateral triangle.

![First Gantt](https://github.com/HORNETJOE/Mathematics/blob/master/picture_11789_Screen_shot_2010-08-09_at_8.35.35_AM.png)

![First Gantt](https://github.com/HORNETJOE/Mathematics/blob/master/picture_6318_Screen_shot_2010-07-08_at_11.53.39_AM.png)

### rate of change within an algebraic function
what is rate of change?

Rate of change describes the average rate at which one quantity is changing with respect to something else changing.
In general, an average rate a change function is a process that calculates the the amount of change in one item divided by the corresponding amount of change in another.

![image](https://github.com/HORNETJOE/Mathematics/blob/master/formla.jpg)

The calculation for thos is located below

	F(x) = x²
	Rate of change from 1 to 3
	(3² - 1²) / (3-1) = (9-1) / (3-1) = 8/2 = 4

	This answer converted into binary is 0100
  
	
    F(x) = 2x+3
    	Rate of change from 10 to 100
	(2*100+3) - (2*10+3) / (100 - 10) = 180/90 = 2

	This answer converted into hexadecimals is 2


### Integral Calculus
Intergral calculas is used to calculate whats inside a curve, if the shape is normal or common then you don't have to use integral calculus. However if the shape is more complex, then you can use the given a and b points on a graph to work out the area of a to b.

![Graph](https://i.imgur.com/NnqLOp3.png)

![Rec](https://i.imgur.com/IGeVbPZ.png)

![image](https://github.com/HORNETJOE/Mathematics/blob/master/formla.jpg)

### Vectors
A vector is a quantity or phenomenon that has two independent properties: magnitudeand direction. The term also denotes the mathematical or geometrical representation of such a quantity.

the link below will direct to the code that uses vecotr to determine shapes
https://github.com/HORNETJOE/Mathematics/blob/master/Code.txt
