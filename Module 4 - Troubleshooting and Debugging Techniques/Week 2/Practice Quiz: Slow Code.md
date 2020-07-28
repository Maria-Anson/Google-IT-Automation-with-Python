# Practice Quiz: Slow Code
> 
> Total points 5
> 
>  1.Question 1
> 
> Which of the following is NOT considered an expensive operation?
> 
> 1 / 1 point 
> 
>  Parsing a file 
> 
>  Downloading data over the network 
> 
>  Going through a list 
> 

      Using a dictionary 
> 
> Check
> 
> Correct
> 
> Awesome! Using a dictionary is faster to look up elements than going through a list.
> 
>  2.Question 2
> 
> Which of the following may be the most expensive to carry out in most automation tasks in a script?
> 
> 1 / 1 point 
> 

      Loops 
> 
>  Lists 
> 
>  Vector 
> 
>  Hash 
> 
> Check
> 
> Correct
> 
> Great work! Loops that run indefinitely, and include subtasks to complete before moving on can be very expensive for most automation tasks.
> 
>  3.Question 3
> 
> Which of the following statements represents the most sound advice when writing scripts?
> 
> 1 / 1 point 
> 
>  Aim for every speed advantage you can get in your code 
> 
>  Use expensive operations often 
> 

      Start by writing clear code, then speed it up only if necessary 
> 
>  Use loops as often as possible 
> 
> Check
> 
> Correct
> 
> Awesome! If we don't notice any slowdown, then there's little point trying to speed it up.
> 
>  4.Question 4
> 
> In Python, what is a data structure that stores multiple pieces of data, in order, which can be changed later?
> 
> 1 / 1 point 
> 
>  A hash 
> 
>  Dictionaries 
> 

      Lists 
> 
>  Tuples 
> 
> Check
> 
> Correct
> 
> Right on! Lists are efficient, and if we are either iterating through the entire list or are accessing elements by their position, lists are the way to go.
> 
>  5.Question 5
> 
> What command, keyword, module, or tool can be used to measure the amount of time it takes for an operation or program to execute? (Check all that apply)
> 
> 1 / 1 point 
> 

      time 
> 
> Check
> 
> Correct
> 
> Excellent! We can precede the name of our commands and scripts with the "time" shell builtin and the shell will output execution time statistics when they complete.
> 

      kcachegrind 
> 
> Check
> 
> Correct
> 
> Nice work! The kcachegrind tool is used for profile data visualization that, if we can insert some code into the program, can tell us how long execution of each function takes.
> 

      cProfile 
> 
> Check
> 
> Correct
> 
> Great job! cProfile provides deterministic profiling of Python programs, including how often and for how long various parts of the program executed.
> 
>  break
>
> -- https://www.coursera.org/learn/troubleshooting-debugging-techniques/quiz/fegKz/practice-quiz-slow-code/view-attempt#Tunnel Vision Close
