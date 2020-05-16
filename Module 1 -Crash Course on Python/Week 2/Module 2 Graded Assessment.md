#Module 2 Graded Assessment
> 
> Latest Submission Grade
> 
> 100%
> 
>  1.Question 1
> 
> Complete the function by filling in the missing parts. The color_translator function receives the name of a color, then prints its hexadecimal value. Currently, it only supports the three additive primary colors (red, green, blue), so it returns "unknown" for all other colors. 
> 
> 

    def color_translator(color):
     
     if color == "red":
     
     hex_color = "#ff0000"
     
     elif color == "green":
     
     hex_color = "#00ff00"
     
     elif color == "blue":
     
     hex_color = "#0000ff"
     
     else:
     
     hex_color = "unknown"
     
     return hex_color
     
     print(color_translator("blue")) # Should be #0000ff
    
     print(color_translator("yellow")) # Should be unknown
     
     print(color_translator("red")) # Should be #ff0000
     
     print(color_translator("black")) # Should be unknown
     
     print(color_translator("green")) # Should be #00ff00
     
     print(color_translator("")) # Should be unknown
     
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
 
     #0000ff
     unknown
     #ff0000
     unknown
     #00ff00
     unknown
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Well done! You're breezing through the if-else clauses!
> 
> </pre>
> 
> 1 / 1 point
> 
>  2.Question 2
> 
> What's the value of this Python expression: "big" > "small" 
> 
>  True 
> 

      False 
> 
>  big 
> 
>  small 
> 
> Check
> 
> Correct
> 
> You nailed it! The conditional operator > checks if two values are equal. The result of that operation is a boolean: either True or False. Alphabetically, "big" is less than "small".
> 
> 1 / 1 point
> 
>  3.Question 3
> 
> What is the elif keyword used for? 
> 
>  To mark the end of the if statement 
> 

      To handle more than two comparison cases 
> 
>  To replace the "or" clause in the if statement 
> 
>  Nothing - it's a misspelling of the else-if keyword 
> 
> Check
> 
> Correct
> 
> You got it! The elif keyword is used in place of multiple embedded if clauses, when a single if/else structure is not enough.
> 
> 1 / 1 point
> 
>  4.Question 4
> 
> Students in a class receive their grades as Pass/Fail. Scores of 60 or more (out of 100) mean that the grade is "Pass". For lower scores, the grade is "Fail". In addition, scores above 95 (not included) are graded as "Top Score". Fill in this function so that it returns the proper grade. 
> 
> 
     def exam_grade(score):
    
     if score>95:
     
     grade = "Top Score"
     
     elif score>=60:
     
     grade = "Pass"
     
     else:
     
     grade = "Fail"
     
    return grade
     
     print(exam_grade(65)) # Should be Pass
     
     print(exam_grade(55)) # Should be Fail
     
     print(exam_grade(60)) # Should be Pass
     
     print(exam_grade(95)) # Should be Pass
    
     print(exam_grade(100)) # Should be Top Score
     
     print(exam_grade(0)) # Should be Fail
     
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

     Pass
     Fail
     Pass
     Pass
     Top Score
     Fail
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Good job! You're getting the hang of it!.
> 
> </pre>
> 
> 1 / 1 point
> 
>  5.Question 5
> 
> What's the value of this Python expression: 11 % 5? 
> 
>  2.2 
> 
>  2 
>

      1 
> 
>  0 
> 
> Check
> 
> Correct
> 
> Excellent! "%" is the modulo operator, which returns the remainder of the integer division between two numbers. 11 divided by 5 equals 2 with remainder of 1.
> 
> 1 / 1 point
> 
>  6.Question 6
> 
> Complete the body of the **_format_name_** function. This function receives the **_first_name_** and **_last_name_** parameters and then returns a properly formatted string.
> 
> Specifically:
> 
> If both the **_last_name_** and the **_first_name_** parameters are supplied, the function should return like so:
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> print(format_name("Ella", "Fitzgerald"))
> 
> Name: Fitzgerald, Ella
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> If only **_one_** name parameter is supplied (either the first name _or_ the last name) , the function should return like so:
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> print(format_name("Adele", ""))
> 
> Name: Adele
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> or
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> print(format_name("", "Einstein"))
> 
> Name: Einstein
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> Finally, if both names are blank, the function should return the empty string:
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 
> print(format_name("", ""))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre>
> 
> Implement below: 
> 
> 

     def format_name(first_name, last_name):

    if first_name != '' and last_name !='':

     return ("Name: " + last_name + ", " + first_name)

     elif first_name == '' and last_name =='':

     return ''

     elif first_name != ' ' or last_name !=' ':

     return ("Name: " + first_name + last_name)

     print(format_name("Ernest", "Hemingway"))

     # Should return the string "Name: Hemingway, Ernest"

     print(format_name("", "Madonna"))

     # Should return the string "Name: Madonna"

     print(format_name("Voltaire", ""))

     # Should return the string "Name: Voltaire"

     print(format_name("", ""))

     # Should return an empty string
 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
>

     Name: Hemingway, Ernest
     Name: Madonna
     Name: Voltaire
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Awesome! You're getting the hang of the multiple and
> embedded "if" clauses!
> 
> </pre>
> 
> 1 / 1 point
> 
>  7.Question 7
> 
> The longest_word function is used to compare 3 words. It should return the word with the most number of characters (and the first in the list when they have the same length). Fill in the blank to make this happen. 
> 

     def longest_word(word1, word2, word3):
    
     if len(word1) >= len(word2) and len(word1) >= len(word3):
     
     word = word1
     
     elif word2>word3:
     
     word = word2
     
     else:
     
     word = word3
     
     return(word)
     
     print(longest_word("chair", "couch", "table"))
     
     print(longest_word("bed", "bath", "beyond"))
     
     print(longest_word("laptop", "notebook", "desktop"))
     
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
    
     chair
     beyond
     notebook
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> You got it! You've figured out how to use an elif clause,
> well done!
> 
> </pre>
> 
> 1 / 1 point
> 
>  8.Question 8
> 
> What’s the output of this code?
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 
     def sum(x, y):
     
         return(x+y)
     
     print(sum(sum(1,2), sum(3,4)))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
> 10
> 
> Check
> 
> Correct
> 
> You nailed it! We’re calling the sum function 3 times: returning 3, then 7, then adding up 3 plus 7 for the total of 10.
> 
> 1 / 1 point
> 
>  9.Question 9
> 
> What's the value of this Python expression?
> 
> ((10 >= 5*2) and (10 <= 5*2)) 
> 
>  True 
> 
>  False 
> 

    10 
> 
>  5*2 
> 
> Check
> 
> Correct
> 
> Right on! When using the "and" operator, a statement is True if both parts of the conditional are True.
> 
> 1 / 1 point
> 
>  10.Question 10
> 
> The fractional_part function divides the numerator by the denominator, and returns just the fractional part (a number between 0 and 1). Complete the body of the function so that it returns the right number. Note: Since division by 0 produces an error, if the denominator is 0, the function should return 0 instead of attempting the division. 
> 
>

     def fractional_part(numerator, denominator):

     if denominator==0:

         val=0
     
     else:

          val=(numerator%denominator)/denominator

     return val

     # Operate with numerator and denominator to

     # keep just the fractional part of the quotient

     print(fractional_part(5, 5)) # Should be 0

     print(fractional_part(5, 4)) # Should be 0.25

     print(fractional_part(5, 3)) # Should be 0.66...

     print(fractional_part(5, 2)) # Should be 0.5

     print(fractional_part(5, 0)) # Should be 0

     print(fractional_part(0, 5)) # Should be 0
 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 
     0.0
     0.25
     0.6666666666666666
     0.5
     0
     0.0
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Well done! You're handling the math operations, as well as
> division by 0, perfectly!
> 
> </pre>
>
> -- https://www.coursera.org/learn/python-crash-course/exam/In52m/module-2-graded-assessment/attempt?redirectToCover=true#Tunnel Vision Close
