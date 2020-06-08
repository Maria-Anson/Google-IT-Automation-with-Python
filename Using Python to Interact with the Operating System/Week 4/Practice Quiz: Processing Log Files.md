# Practice Quiz: Processing Log Files
> 
> Total points 5
> 
>  1.Question 1
> 
> You have created a Python script to read a log of users running CRON jobs. The script needs to accept a command line argument for the path to the log file. Which line of code accomplishes this?
> 
> 1 / 1 point 
> 
>  import sys 
> 

      syslog=sys.argv[1] 
> 
>  print(line.strip()) 
> 
>  usernames = {} 
> 
> Check
> 
> Correct
> 
> Right on! This will assign the script's first command line argument to the variable "syslog".
> 
>  2.Question 2
> 
> Which of the following is a data structure that can be used to count how many times a specific error appears in a log?
> 
> 1 / 1 point 
> 
>  Get 
> 
>  Continue 
> 
>  Search 
> 

      Dictionary 
> 
> Check
> 
> Correct
> 
> Great work! A dictionary is useful to count appearances of strings.
> 
>  3.Question 3
> 
> Which keyword will return control back to the top of a loop when iterating through logs?
> 
> 1 / 1 point 
> 

      Continue 
> 
>  Get 
> 
>  With 
> 
>  Search 
> 
> Check
> 
> Correct
> 
> Excellent! The continue statement is used to return control back to the top of a loop.
> 
>  4.Question 4
> 
> When searching log files using regex, which regex statement will search for the alphanumeric word "IP" followed by one or more digits wrapped in parentheses using a capturing group?
> 
> 1 / 1 point 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> r"IP \(\d+\)$"
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> b"IP \((\w+)\)$"
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 

     r"IP \((\d+)\)$"
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 
> r"IP \((\D+)\)$" 
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
> Check
> 
> Correct
> 
> Awesome! This expression will search for the word "IP" followed by a space and parentheses. It uses a capture group and \d+ to capture any digit characters found in the parentheses.
> 
>  5.Question 5
> 
> Which of the following are true about parsing log files? (Select all that apply.)
> 
> 1 / 1 point 
> 
>  Load the entire log files into memory. 
> 

      You should parse log files line by line. 
> 
> Check
> 
> Correct
> 
> Well done! Since log files can get pretty large, it's a good idea to parse them one line at a time instead of loading the entire file into memory at once.
> 

      It is efficient to ignore lines that don't contain the information we need. 
> 
> Check
> 
> Correct
> 
> Right on! We can save a lot of time by not parsing lines that don't contain what we need.
> 
    
    We have to **_open()_** the log files first. 
> 
> Check
> 
> Correct
> 
> Nice job! Before we can parse our log file, we have to use the **_open()_** or **_with open()_** command on the file first.
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/FIFJz/practice-quiz-processing-log-files/attempt?redirectToCover=true#Tunnel Vision Close
