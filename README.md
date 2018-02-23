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
