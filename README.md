# 100DaysOfCode_Python
All Python Exercises of CodeWithHarry 100DaysOfCode Python Tutorial
<details>
    <summary>Python Exercise 1</summary>
  <br>
  Exercise : Take two inputs from the user and print values after applying all the airthmetic functions.
  <br><br>
  
Output Should be like this:
```
enter first number :4
enter second number : 8
addition of given two numbers is  12
diffrence of given two numbers is  -4
by multiplying given two number we get  32
by dividing the given two number we get  0.5
```

Solution : [Click here](https://github.com/mistabaaz/100DaysOfCode_Python/blob/main/ex1_calculator.py)
 
---
  
</details>

<details>
    <summary>Python Exercise 2</summary>
  <br>
  Exercise : Greet the user according to the day.For example if it is morning then your program should greet with "Good Morning Sir!" and if it is noon then "Good Afternoon Sir!" and so on. Without asking time from the user.
  <br><br>
  
Output Should be like this:
    
```
Good Evening Sir!
```

Solution : [Click here](https://github.com/mistabaaz/100DaysOfCode_Python/blob/main/ex2_good_morning_sir.py)
 
---
  
</details>

<details>
    <summary>Python Exercise 3</summary>
  <br>
  Exercise : Make a quiz like KBC(Kaun Banega Crorepati).Display all the questions and 4 options.100 rupees will be given for 1 correct answer and a penalty of 100 rupees for 1 wrong answer.Display the results after end of the qestions.
  <br><br>
  
Output Should be like this:
    
```
          Question Number 1

What is the Capital of India?
1.Chandigrah
2.Gujrat
3.Delhi
4.Haryana

Note: Enter only option like 1/2/3/4
Choose the correct option: 3

Horray! You have chosen the right answer: 3.Delhi
You win 100 rupees.

          Question Number 2

When Haryana was separated from Punjab?
1.In 1857
2.In 1947
3.In 2010
4.In 1991

Note: Enter only option like 1/2/3/4
Choose the correct option: 3

Oops! You chosen the wrong answer.
Correct Answer is: 4.In 1991
You Lose 100 rupees.

Now it's time to check your results!
You have given 1 right answers in total and 1 wrong answers.
Therefore

You Lose total of 0 rupees
```
<br>
Hint: You may use a list for storing questions and answers.
    <br><br>
    
Solution : [Click here](https://github.com/mistabaaz/100DaysOfCode_Python/blob/main/ex3_kbc.py)
 
---
  
</details>

<details>
    <summary>Python Exercise 4</summary>
  <br>
  Exercise : Make a program to encode & decode user's text messages.
  <br><br>
  
Output Should be like this:
    
```
***************Main Menu***************
1.Encode the message
2.Decode the message
3.Exit

Choose the Correct Option(1/2/3...): 1

Enter A Text Message: hello whats'up

Your message will be Encoded soon...
Encoded message is here: 
oXsellohqr[ AF^hats'upweQT 


***************Main Menu***************
1.Encode the message
2.Decode the message
3.Exit

Choose the Correct Option(1/2/3...): 2

Enter Encoded Text Message: oXsellohqr[ AF^hats'upweQT

Your message will be Decoded soon...
Your Decoded message is here: 
hello whats'up 


***************Main Menu***************
1.Encode the message
2.Decode the message
3.Exit

Choose the Correct Option(1/2/3...): 3

You will be exiting soon...
```
    
Methods to Encode a single word:
- if word length is less than 3 then reverse the word (i.e ok --> ko)
- otherwise put first letter of the word into last (and remover it from the beginning i.e hello-->elloh)
- then add random three letters in the begining as well as ending (i.e elloh-->kidellohmin)

    <br>
    
Methods to Decode a single word:
- check if the length of the word is less than 3 if yes then reverse the word (i.e ko-->ok)
- otherewise remove 3 letters of the word from both the beginning and ending (i.e kidellohmin --> elloh)
- after that put the last letter of the word to the beginning (i.e elloh --> hello)

Solution : [Click here](https://github.com/mistabaaz/100DaysOfCode_Python/blob/main/ex4_secret_language.py)
 
---
  
</details>
