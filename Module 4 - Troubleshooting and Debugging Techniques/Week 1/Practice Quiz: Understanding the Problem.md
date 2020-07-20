# Practice Quiz: Understanding the Problem
> 
> Total points 5
> 
>  1.Question 1
> 
> When a user reports that an "application doesn't work," what is an appropriate follow-up question to gather more information about the problem?
> 
> 1 / 1 point 
> 
>  Is the server plugged in? 
> 
>  Why do you need the application? 
> 
>  Do you have a support ticket number? 
> 

      What should happen when you open the app? 
> 
> Check
> 
> Correct
> 
> Awesome! Asking the user what an expected result should be will help you gather more information to understand and isolate the problem.
> 
>  2.Question 2
> 
> What is a heisenbug?
> 
> 1 / 1 point 
> 

      The observer effect. 
> 
>  A test environment. 
> 
>  The root cause. 
> 
>  An event viewer. 
> 
> Check
> 
> Correct
> 
> Right on! The observer effect is when just observing a phenomenon alters the phenomenon.
> 
>  3.Question 3
> 
> The compare_strings function is supposed to compare just the alphanumeric content of two strings, ignoring upper vs lower case and punctuation. But something is not working. Fill in the code to try to find the problems, then fix the problems.
> 
> 1 / 1 point 
>
> def compare_strings(string1, string2):
> 
>   #Convert both strings to lowercase 
> 
>   #and remove leading and trailing blanks
> 
>   string1 = string1.lower().strip()
> 
>   string2 = string2.lower().strip()
> 
>   #Ignore punctuation
> 
>   punctuation = r"[-.?!,;:']"
> 
>   #DEBUG CODE GOES HERE
> 
>   print(string1,string2)
> 
>   return string1 == string2
> 
> print(compare_strings("Have a Great Day!", "Have a great day?")) # True
> 
> print(compare_strings("It's raining again.", "its raining, again")) # True
> 
> print(compare_strings("Learn to count: 1, 2, 3.", "Learn to count: one, two, three.")) # False
> 
> import re
> 
>   string1 = re.sub(punctuation, r"", string1)
> 
>   string2 = re.sub(punctuation, r"", string2)
> 
> print(compare_strings("They found some body.", "They found somebody.")) # False
> 
> Enter to Rename, Shift+Enter to Preview
> 
> .monaco-list.list_id_4:focus .monaco-list-row.focused { background-color: #d6ebff; } .monaco-list.list_id_4:focus .monaco-list-row.focused:hover { background-color: #d6ebff; } .monaco-list.list_id_4:focus .monaco-list-row.selected { background-color: #0069d1; } .monaco-list.list_id_4:focus .monaco-list-row.selected:hover { background-color: #0069d1; } .monaco-list.list_id_4:focus .monaco-list-row.selected { color: #ffffff; } .monaco-drag-image, .monaco-list.list_id_4:focus .monaco-list-row.selected.focused { background-color: #0074e8; } .monaco-drag-image, .monaco-list.list_id_4:focus .monaco-list-row.selected.focused { color: #ffffff; } .monaco-list.list_id_4 .monaco-list-row.focused { background-color: #d6ebff; } .monaco-list.list_id_4 .monaco-list-row.focused:hover { background-color: #d6ebff; } .monaco-list.list_id_4 .monaco-list-row.selected { background-color: #e4e6f1; } .monaco-list.list_id_4 .monaco-list-row.selected:hover { background-color: #e4e6f1; } .monaco-list.list_id_4:not(.drop-target) .monaco-list-row:hover:not(.selected):not(.focused) { background-color: #f0f0f0; } .monaco-list.list_id_4.drop-target, .monaco-list.list_id_4 .monaco-list-rows.drop-target, .monaco-list.list_id_4 .monaco-list-row.drop-target { background-color: #d6ebff !important; color: inherit !important; } .monaco-list-type-filter { background-color: #efc1ad } .monaco-list-type-filter { border: 1px solid rgba(0, 0, 0, 0); } .monaco-list-type-filter.no-matches { border: 1px solid #be1100; } .monaco-list-type-filter { box-shadow: 1px 1px 1px #a8a8a8; }
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 
> have a great day have a great day
> True
> its raining again its raining again
> True
> learn to count 1 2 3 learn to count one two three
> False
> they found some body they found somebody
> False
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Great job! These bugs don't stand a chance with you around!
> 
> </pre>
> 
>  4.Question 4
> 
> How do we verify if a problem is still persisting or not?
> 
> 1 / 1 point 
> 
>  Restart the device or server hardware 
> 

      Attempt to trigger the problem again by following the steps of our reproduction case 
> 
>  Repeatedly ask the user 
> 
>  Check again later 
> 
> Check
> 
> Correct
> 
> Woohoo! If we can recreate the circumstances of the issue, we can verify whether the problem continues to occur.
>
> -- https://www.coursera.org/learn/troubleshooting-debugging-techniques/quiz/Re6c1/practice-quiz-understanding-the-problem/attempt?redirectToCover=true#Tunnel Vision Close
