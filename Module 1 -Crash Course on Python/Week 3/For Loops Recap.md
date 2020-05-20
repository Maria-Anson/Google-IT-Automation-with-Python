> ## For Loops Recap
> 
> * * *
> 
> _For_ loops allow you to iterate over a sequence of values. Let's take the example from the beginning of the video:
> 
> for x in range(5):
> 
>   print(x)
> 
> Similar to _if_ statements and _while_ loops, _for_ loops begin with the keyword **_for_** with a colon at the end of the line. Just like in function definitions, _while_ loops and _if_ statements, the body of the _for_ loop begins on the next line and is indented to the right. But what about the stuff in between the _for_ keyword and the colon? In our example, we’re using the _range()_ function to create a sequence of numbers that our _for_ loop can iterate over. In this case, our variable **x** points to the current element in the sequence as the _for_ loop iterates over the sequence of numbers. Keep in mind that in Python and many programming languages, a range of numbers will start at 0, and the list of numbers generated will be one less than the provided value. So _range(5)_ will generate a sequence of numbers from 0 to 4, for a total of 5 numbers.
> 
> Bringing this all together, the range(5) function will create a sequence of numbers from 0 to 4\. Our _for_ loop will iterate over this sequence of numbers, one at a time, making the numbers accessible via the variable **x** and the code within our loop body will execute for each iteration through the sequence. So for the first loop, **x** will contain 0, the next loop, 1, and so on until it reaches 4\. Once the end of the sequence comes up, the loop will exit and the code will continue.
> 
> The power of _for_ loops comes from the fact that it can iterate over a sequence of any kind of data, not just a range of numbers. You can use _for_ loops to iterate over a list of strings, such as usernames or lines in a file.
> 
> Not sure whether to use a _for_ loop or a _while_ loop? Remember that a _while_ loop is great for performing an action over and over until a condition has changed. A _for_ loop works well when you want to iterate over a sequence of elements.
>
> -- https://www.coursera.org/learn/python-crash-course/supplement/FCEnY/for-loops-recap#main
