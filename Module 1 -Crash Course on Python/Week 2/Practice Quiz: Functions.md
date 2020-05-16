   
   # Practice Quiz: Functions

> 
> Total points 5
> 
>  1.Question 1
> 
> This function converts miles to kilometers (km).
> 
> 1.  Complete the function to return the result of the conversion
> 2.  Call the function to convert the trip distance from miles to kilometers
> 3.  Fill in the blank to print the result of the conversion
> 4.  Calculate the round-trip in kilometers by doubling the result, and fill in the blank to print the result 
> 
>

    1) Complete the function to return the result of the conversion
     
    def convert_distance(miles):
     
    km = miles * 1.6
     
    return km
     
    # approximately 1.6 km in 1 mile
     
    my_trip_miles = 55
     
    # 2) Convert my_trip_miles to kilometers by calling the function above
     
    my_trip_km = convert_distance(my_trip_miles)
     
    # 3) Fill in the blank to print the result of the conversion
     
    print("The distance in kilometers is " + str(my_trip_km))
     
    # 4) Calculate the round-trip in kilometers by doubling the result,
     
    # and fill in the blank to print the result
     
    print("The round-trip in kilometers is " + str(2*my_trip_km))
     

> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
>

     The distance in kilometers is 88.0
     The round-trip in kilometers is 176.0
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Woohoo! You’ve figured out how to make the functions do what
> they need to do, and remembered some things from the
> previous lessons. Way to go!.
> 
> </pre>
> 
> 1 / 1 point
> 
>  2.Question 2
> 
> This function compares two numbers and returns them in increasing order.
> 
> 1.  Fill in the blanks, so the print statement displays the result of the function call in order.
> 
> Hint: if a function returns multiple values, don't forget to store these values in multiple variables 
> 
> 

     # This function compares two numbers and returns them
     
     # in increasing order.
     
     def order_numbers(number1, number2):
     
     if number2 > number1:
     
     return number1, number2
     
     else:
     
     return number2, number1
     
     # 1) Fill in the blanks so the print statement displays the result
     
     # of the function call
     
     smaller, bigger = order_numbers(100, 99)
    > 
     print(smaller, bigger)
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
>

    > 99 100
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Nice! You remembered how to accept multiple return values
> from a function. You’re ready for the next lesson!
> 
> </pre>
> 
> 1 / 1 point
> 
>  3.Question 3
> 
> What are the values passed into functions as input called? 
> 
>  Variables 
> 
>  Return values 
>

    Parameters 
> 
>  Data types 
> 
> Check
> 
> Correct
> 
> Nice job! A parameter, also sometimes called an argument, is a value passed into a function for use within the function.
> 
> 1 / 1 point
> 
>  4.Question 4
> 
> Let's revisit our lucky_number function. We want to change it, so that instead of printing the message, it returns the message. This way, the calling line can print the message, or do something else with it if needed. Fill in the blanks to complete the code to make it work. 
> 
> 

     def lucky_number(name):
     
     number = len(name) * 9
     
     ans = "Hello " + name + ". Your lucky number is " + str(number)
     
     return ans
     
     print(lucky_number("Kay"))
     
     print(lucky_number("Cameron"))
     
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
>

     Hello Kay. Your lucky number is 27
     Hello Cameron. Your lucky number is 63
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Way to go! The function now returns the message, for the
> calling line to use it in any way it wants to.
> 
> </pre>
> 
> 1 / 1 point
> 
>  5.Question 5
> 
> What is the purpose of the def keyword? 
> 

      Used to define a new function 
> 
>  Used to define a return value 
> 
>  Used to define a new variable 
> 
>  Used to define a new parameter 
> 
> Check
> 
> Correct
> 
> Awesome! When defining a new function, we must use the def keyword followed by the function name and properly indented body.
>
> -- https://www.coursera.org/learn/python-crash-course/quiz/hqfxs/practice-quiz-functions/attempt?redirectToCover=true#Tunnel Vision Close
