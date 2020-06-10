# Practice Quiz: Interacting with the Command Line
> 
> Total points 5
> 
>  1.Question 1
> 
> Which of the following commands will redirect errors in a script to a file?
> 
> 1 / 1 point 
> 

      user@ubuntu:~$ ./calculator.py 2> error_file.txt 
> 
>  user@ubuntu:~$ ./calculator.py >> error_file.txt 
> 
>  user@ubuntu:~$ ./calculator.py > error_file.txt 
> 
>  user@ubuntu:~$ ./calculator.py < error_file.txt 
> 
> Check
> 
> Correct
> 
> You nailed it! The "2>" sign will redirect errors to a file.
> 
>  2.Question 2
> 
> When running a kill command in a terminal, what type of signal is being sent to the process?
> 
> 1 / 1 point 
> 
>  SIGINT 
> 
>  PID 
> 
>  SIGSTOP 
> 

      SIGTERM 
> 
> Check
> 
> Correct
> 
> You got it! The kill command sends a SIGTERM signal to a processor ID (PID) to terminate.
> 
>  3.Question 3
> 
> What is required in order to read from standard input using Python?
> 
> 1 / 1 point 
> 
>  echo file.txt 
> 
>  cat file.txt 
> 
>  The file descriptor of the STDIN stream 
> 

      Stdin file object from sys module 
> 
> Check
> 
> Correct
> 
> Right on! Using sys.stdin, we can read from standard input in Python.
> 
>  4.Question 4
> 
> _____ are tokens delivered to running processes to indicate a desired action.
> 
> 1 / 1 point 
> 

      Signals 
> 
>  Methods 
> 
>  Functions 
> 
>  Commands 
> 
> Check
> 
> Correct
> 
> Nice job! Using signals, we can tell a program that we want it to pause or terminate, or many other possible commands.
> 
>  5.Question 5
> 
> In Linux, what command is used to display the contents of a directory?
> 
> 1 / 1 point 
> 
>  rmdir 
> 
>  cp 
> 
>  pwd 
> 

      ls 
> 
> Check
> 
> Correct
> 
> Nice job! The ls command lists the file contents of a directory.
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/8AsfN/practice-quiz-interacting-with-the-command-line/attempt?redirectToCover=true#Tunnel Vision Close
