#fortune teller program

User gives some information about themselves and the program tells their fortune.

REMEMBER: There is no right answer!!!! If your code meets the program requirements, then it works.

## Concepts
- different types of input and arguments (review gets.chomp and ARGV. also review arguments)
- variable types (string, integer, float, boolean) and use of to_i (http://apidock.com/ruby/String/to_i), to_s, etc
- conditionals (if/else statements) (http://www.tutorialspoint.com/ruby/ruby_if_else.htm)
- case statements (https://www.blackbytes.info/2015/10/ruby-case/)
- using boolean logic (https://learnrubythehardway.org/book/ex27.html and 28 - this person says to memorize these tables, that doesn't make sense. don't do that ;))

## Program Requirements
1. User can enter their name and program responds, "Hi, [user name]"

2. User can input age and program repeats information back to user  
*discuss difference between string, integer and float

3. User can decide whether or not they want their fortune told and program responds.  
*discuss boolean

4. If user decides to have their fortune told, program asks one detail about the user (remember - is the answer to the question an integer, a boolean or a string?). Depending on this detail, the program tells the user's fortune.  
*discuss conditionals

5. User is asked more than one detail about their life and program tells fortune depending on those details.

6. Play with your code and make the combinations more complex  
*discuss 'case statements'


Example output:

Welcome to the fortune teller game!  
What's your name?  
\> Laura  
Hi, Laura!  
How old are you?  
\> 29  
You are 29 years old.  
Would you like me to tell your fortune? (y/n)  
\> y  
Great, here we go!  
Do you like ice cream? (y/n)  
\> y  
Do you have your period right now? (y/n)  
\> n  
What is your job?  
\> Programmer  
What is your zodiac sign?  
\> Aquarius  
Pick a number between 1 and 10:  
\> 9  
*********************************  
I am thinking..................  
Your fortune is:  
You will get your period tomorrow and eat lots of ice cream!  
*********************************  
Do you want another fortune? (y/n)  
\> n  
OK, goodbye!
