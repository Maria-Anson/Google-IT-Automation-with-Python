# Practice Quiz: Conditionals
> 
> Total points 5
> 
>  1.Question 1
> 
> What's the value of this Python expression: (2**2) == 4? 
> 
>  4 
> 
>  2**2 
> 

    >  True 
> 
>  False 
> 
> Check
> 
> Correct
> 
> You nailed it! The conditional operator == checks if two values are equal. The result of that operation is a boolean: either True or False.
> 
> 1 / 1 point
> 
>  2.Question 2
> 
> Complete the script by filling in the missing parts. The function receives a name, then returns a greeting based on whether or not that name is "Taylor". 
> 
>

    > def greeting(name):
    > 
    > if name == "Taylor":
    > 
    > return "Welcome back Taylor!"
    > 
    > else:
    > 
    > return "Hello there, " + name
    > 
    > print(greeting("Taylor"))
    > 
    > print(greeting("John"))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

    > Welcome back Taylor!
    > Hello there, John
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Great work! You're getting the hang of conditionals in Python.
> 
> </pre>
> 
> 1 / 1 point
> 
>  3.Question 3
> 
> What’s the output of this code if number equals 10?
> 
> <pre contenteditable="false" data-language="python" tabindex="0" style="opacity: 1;">
> 
> 

    > if number > 11: 
    > 
    >   print(0)
    > 
    > elif number != 10:
    > 
    >   print(1)
    > 
    > elif number >= 20 or number < 12:
    > 
    >   print(2)
    > 
    > else:
    > 
    >   print(3)
    > 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
> 2
> 
> Check
> 
> Correct
> 
> Right on! Our number is 10, which is smaller than 12, so it matches that condition.
> 
> 1 / 1 point
> 
>  4.Question 4
> 
> Is "A dog" smaller or larger than "A mouse"? Is 9999+8888 smaller or larger than 100*100? Replace the plus sign in the following code to let Python check it for you and then answer.
> 
> <pre contenteditable="false" data-language="python" data-evaluator-id="XlimjpZdT3CYpo6WXd9wmQ@3" tabindex="0" style="opacity: 1;">
> 
> 1
> 
> 2
> 

    > print("A dog" > "A mouse")
    > 
    > print((9999+8888) > (100*100))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

    > False
    > True
> 
> </pre>
> 
> </pre> 
> 
>  "A dog" is larger than "A mouse" and 9999+8888 is larger than 100*100 
> 

    >  "A dog" is smaller than "A mouse" and 9999+8888 is larger than 100*100 
> 
>  "A dog" is larger than "A mouse" and 9999+8888 is smaller than 100*100 
> 
>  "A dog" is smaller than "A mouse" and 9999+8888 is smaller than 100*100 
> 
> Check
> 
> Correct
> 
> You got it! Keep getting Python to do the work for you.
> 
> 1 / 1 point
> 
>  5.Question 5
> 
> If a filesystem has a block size of 4096 bytes, this means that a file comprised of only one byte will still use 4096 bytes of storage. A file made up of 4097 bytes will use 4096*2=8192 bytes of storage. Knowing this, can you fill in the gaps in the calculate_storage function below, which calculates the total number of bytes needed to store a file of a given size? 
> 
> 

    > def calculate_storage(filesize):
    > 
    > block_size = 4096
    > 
    > # Use floor division to calculate how many blocks are fully occupied
    > 
    > full_blocks = filesize//block_size
    > 
    > # Use the modulo operator to check whether there's any remainder
    > 
    > partial_block_remainder = filesize%block_size
    > 
    > # Depending on whether there's a remainder or not, return
    > 
    > # the total number of bytes required to allocate enough blocks
    > 
    > # to store your data.
    > 
    > if partial_block_remainder > 0:
    > 
    > return full_blocks*4096 + 4096
    > 
    > return full_blocks * 4096
    > 
    > print(calculate_storage(1)) # Should be 4096
    > 
    > print(calculate_storage(4096)) # Should be 4096
    > 
    > print(calculate_storage(4097)) # Should be 8192
    > 
    > print(calculate_storage(6000)) # Should be 8192
    > 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

    > 4096
    > 4096
    > 8192
    > 8192
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Awesome! Those were some complicated calculations that you
> needed to do, but you did it!
> 
> </pre>
>
> -- https://www.coursera.org/learn/python-crash-course/quiz/QrKqf/practice-quiz-conditionals/attempt?redirectToCover=true#Tunnel Vision Close
