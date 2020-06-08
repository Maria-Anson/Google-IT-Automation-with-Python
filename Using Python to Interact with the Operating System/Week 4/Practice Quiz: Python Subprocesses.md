# Practice Quiz: Python Subprocesses
> 
> Total points 5
> 
>  1.Question 1
> 
> What type of object does a run function return?
> 
> 1 / 1 point 
> 
>  stdout 
> 
>  capture_output 
> 
>  returncode 
> 

      CompletedProcess 
> 
> Check
> 
> Correct
> 
> Awesome! This object includes information related to the execution of a command.
> 
>  2.Question 2
> 
> How can you change the current working directory where a command will be executed?
> 
> 1 / 1 point 
> 
>  Use the capture_output parameter. 
> 

      Use the cwd parameter. 
> 
>  Use the env parameter. 
> 
>  Use the shell parameter. 
> 
> Check
> 
> Correct
> 
> Right on! This will change the current working directory where the command will be executed.
> 
>  3.Question 3
> 
> When a child process is run using the subprocess module, which of the following are true? (check all that apply)
> 
> 1 / 1 point 
> 

      The child process is run in a secondary environment. 
> Check
> 
> Correct 

      The parent process is blocked while the child process finishes. 
> 
> Check
> 
> Correct
> 
> Excellent! While the parent process is waiting on the subprocess to finish, it’s blocked, meaning the parent can’t do any work until the child finishes.
> 
>  The parent process and child process both run simultaneously. 
> 

      Control is returned to the parent process when the child process ends. 
> 
> Check
> 
> Correct
> 
> Right on! After the external command completes its work, the child process exits, and the flow of control returns to the parent.
> 
> You didn’t select all the correct answers
> 
>  4.Question 4
> 
> When using the **_run_** command of the subprocess module, what parameter, when set to True, allows us to store the output of a system command?
> 
> 1 / 1 point 
> 
>  cwd 
> 

      capture_output 
> 
>  timeout 
> 
>  shell 
> 
> Check
> 
> Correct
> 
> Excellent! The capture_output parameter allows us to get and store the output of the system command we're using.
> 
>  5.Question 5
> 
> What does the copy method of os.environ do?
> 
> 1 / 1 point 
> 

      Creates a new dictionary of environment variables 
> 
>  Runs a second instance of an environment 
> 
>  Joins two strings 
> 
>  Removes a file from a directory 
> 
> Check
> 
> Correct
> 
> Nice work! The copy method of os.environ makes a new copy of the dictionary containing the environment variables, making modification easier.
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/WDRRe/practice-quiz-python-subprocesses/attempt?redirectToCover=true#Tunnel Vision Close
