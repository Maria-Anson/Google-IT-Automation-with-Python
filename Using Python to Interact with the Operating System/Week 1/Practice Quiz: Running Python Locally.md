# Practice Quiz: Running Python Locally
> 
> Total points 5
> 
>  1.Question 1
> 
> When your IDE automatically creates an indent for you, this is known as what? 
> 
>  Syntax highlighting 
> 

      Code completion 
> 
>  Interpreted language 
> 
>  Code reuse 
> 
> Check
> 
> Correct
> 
> Nicely done! Code completion is an IDE feature that takes educated guesses about what you might be trying to type next, and offers suggestions to complete it for you.
> 
> 1 / 1 point
> 
>  2.Question 2
> 
> Can you identify the error in the following code?
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
>
> #!/usr/bin/env python3
> 
> import numpy as np
> 
> def numpyArray():
> 
>     x = np.array([[1, 2, 3], [4, 5, 6]], np.int32)
> 
>     y = numpy.array([[3, 6, 2], [9, 12, 8]], np.int32)
> 
>     return x*y
> 
> print(numpyArray())
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  The function is not indented properly. 
> 
>  numpy is not imported correctly because as is used. 
> 

      The y variable is not calling the numpy module properly. 
> 
>  The shebang line is not necessary. 
> 
> Check
> 
> Correct
> 
> Nice job! While the x variable is calling numpy using its declared local name, y is not using the local name. This will result in an error.
> 
> 1 / 1 point
> 
>  3.Question 3
> 
> Which type of programming language is read and converted to machine code before runtime, allowing for more efficient code? 
> 
>  Object-oriented language 
> 

      Compiled language 
> 
>  Interpreted language 
> 
>  Intermediate code 
> 
> Check
> 
> Correct
> 
> Awesome! A compiled language is translated into code readable by the target machine during development using a compiler.
> 
> 1 / 1 point
> 
>  4.Question 4
> 
> Which of the following is not an IDE or code editor? 
> 
>  Eclipse 
> 

      pip 
> 
>  Atom 
> 
>  PyCharm 
> 
> Check
> 
> Correct
> 
> Right on! The package manager pip is used in Python to install packages from repositories such as PyPI.
> 
> 1 / 1 point
> 
>  5.Question 5
> 
> What does the PATH variable do? 
> 

      Tells the operating system where to find executables 
> 
>  Returns the current working directory 
> 
>  Holds the command line arguments of your Python program in a list 
> 
>  Tells the operating system where to cache frequently used files 
> 
> Check
> 
> Correct
> 
> Nice work! The PATH variable tells the operating system where to find executables.
> 
> 1 / 1 point
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/6sTaq/practice-quiz-running-python-locally/attempt?redirectToCover=true#Tunnel Vision Close
