# Practice Quiz - Advanced Bash Concepts
> 
> Total points 5
> 
>  1.Question 1
> 
> Which command does the while loop initiate a task(s) after?
> 
> 1 / 1 point 
> 
>  while 
> 

      do 
> 
>  done 
> 
>  n=1 
> 
> Check
> 
> Correct
> 
> Awesome! Tasks to be performed are written after do.
> 
>  2.Question 2
> 
> Which line is correctly written to start a FOR loop with a sample.txt file?
> 
> 1 / 1 point 
> 
>  for sample.txt do in file 
> 
>  for sample.txt in file; do 
> 

      for file in sample.txt; do 
> 
>  do sample.txt for file 
> 
> Check
> 
> Correct
> 
> You nailed it! The contents of sample.txt are loaded into a file variable which will do any specified task.
> 
>  3.Question 3
> 
> Which of the following Bash lines contains the condition of taking an action when n is less than or equal to 9?
> 
> 1 / 1 point 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 1
> 

     while [ $n -le 9 ]; dowhile [ $n -le 9 ]; do
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 1
> 
> while [ $n -lt 9 ]; do
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 1
> 
> while [ $n -ge 9 ]; do
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
>  <pre contenteditable="false" data-language="python" style="opacity: 1;" tabindex="0">
> 
> 1
> 
> while [ $n -ot 9 ]; do
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> </pre> 
> 
> Check
> 
> Correct
> 
> Right on!. This line will take an action when n is less than or equal to 9.
> 
>  4.Question 4
> 
> Which of the following statements are true regarding Bash and Python? [Check all that apply]
> 
> 1 / 1 point 
> 

      Complex scripts are better suited to Python. 
> 
> Check
> 
> Correct
> 
> Nice work! When a script is complex, it's better to write it in a more general scripting language, like Python.
> 
>  Bash scripts work on all platforms. 
> 

      Python can more easily operate on strings, lists, and dictionaries. 
> 
> Check
> 
> Correct
> 
> Awesome! Bash scripts aren’t as flexible or robust as having the entire Python language available, with its many different functions to operate on strings, lists, and dictionaries.
> 
    
      If a script requires testing, Python is preferable. 
> 
> Check
> 
> Correct
> 
> Right on! Because of the ease of testing and the fact that requiring testing implies complexity, Python is preferable for code requiring verification.
> 
>  5.Question 5
> 
> The _____ command lets us take only bits of each line using a field delimiter.
> 
> 1 / 1 point 
> 

      cut 
> 
>  echo 
> 
>  mv 
> 
>  sleep 
> 
> Check
> 
> Correct
> 
> Excellent!  The cut command lets us take only bits of each line using a field delimiter.
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/ITxzb/practice-quiz-advanced-bash-concepts/attempt?redirectToCover=true#Tunnel Vision Close
