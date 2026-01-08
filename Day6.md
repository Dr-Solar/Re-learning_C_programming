Hello guys to the day 6 of C programming.Today we start with the problem "Get a two digit  number from the user and substract 5 from it if the sum of its digits is odd and print the result".
This problem is a bit tricky but i can use the same trick that i used for problem no 21 in the assessment ( no 18 in my code).
The idea is first find the individual digits and add them to different variables, in this case i need 2 variables.
Then i need the sum of the digits so yeah a simple a+b form .
Now comes first obstacle how to find if it is odd . 
For that just follow basic math and divide it by 2 and get the reminder ( odd gives 1 & even gives 0).
Using this we can arrive at the point where odd and even is recognisable **for us**.
Now nextobstacle we need the computer or compiler to know if the sum is odd and do operation . 
since we cant use if or any other condition we cant make the computer understand the sum is odd. 
But we can make the computer do the operation or else it wont be given in assessment.
So how, after thinking we need to do some trial and error or formulate a formula .
For me a formula/equation works.
What i did was make a verbal conditon  without using if or anything else.

So it goes like this " Consider : sum/2=y, then y= 1 then take z=(x-5)*y this will substract 5 from the number if sum is odd, But if the sum is even the z will become 0 using this formula.
We need to print the same number if the sum is even .So we need another formula for this.   So my idea was to add the number** x** to **z** and then substract the product of **x** and **y** from the above result.
This will give the number on screen when the sum is even. The formula goes like this 'z= z + (1-y)*x',The formula is shortened " 
Do this and the problem solved.


Next problem is "Get a three digit number from the user and substract 5 from it if the one's digit and 100's digit are both odd and then print the result" This problem is almost same as earlier one
Find the one's and hundred's digit and assign them to each variable z&y. 
Then divide both individually by 2 and store the remainders in same variables.
Then get product of z&y and assign the value to y
Then do the rest of the steps we did earlier.


Next problem is "Get a three digit number from user.If sum of digits is less than 10 print sum.Otherwise add the digits of the sum ,if that is less than 10 then print sum 
if not then do it again until we get a single digit number as result"
This is completely different from the recent problems , it was a bit difficult for me to crack.
I needed to think stepwise :1 the sum of digits is less than 10, 2 the sum of digits is greater than 10 and sum of digits os previous sum is less than 10,
3 The sum of the digits of the number is greater than 10 and sum of digits of the previous sum is greater than 10 and the sum of digits of previous sum is less than 10.

First i made code for the step 1 got value for first number in the problem . then on to step 2 but then i got a issue . i got the second number in problem correct but first number answer shows zero 
So i fine tuned the code so that both numbers can give me the desired answer.
Then i went on to the third step the last number in the problem. I made extra lines in the code for the third number as well. But as earlier when i execute the program the error came again
So i fine tuned the code again and reached the final code.
After running the code it successfully run and i got desired results for thw three numbers in the problem.

Sorry for not explaining more clearly the problem no 25 just weared me out since i spend around an hour and half on it.

Next question is "Get a three digit number from the user and make the ten's digit zero and print the result "
This problem was so easy just find the ten's digit and multiply it by 10 
Then substract the result from the number from user 
Then print the result 

Next question is ""


