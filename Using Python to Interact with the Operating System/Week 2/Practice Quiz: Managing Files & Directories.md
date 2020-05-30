# Practice Quiz: Managing Files & Directories
> 
> Total points 5
> 
>  1.Question 1
> 
> The create_python_script function creates a new python script in the current working directory, adds the line of comments to it declared by the 'comments' variable, and returns the size of the new file. Fill in the gaps to create a script called "program.py". 

     def create_python_script(filename):
     
      comments = "# Start of a new Python program"
     
      with open(filename,"w") as file:
    
      filesize = file.write(comments)
     
      return(filesize)
     
     print(create_python_script("program.py"))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

     31
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Great work! Your new python script is now ready for some
> real code!
> 
> </pre>
> 
> 1 / 1 point
> 
>  2.Question 2
> 
> The new_directory function creates a new directory inside the current working directory, then creates a new empty file inside the new directory, and returns the list of files in that directory. Fill in the gaps to create a file "script.py" in the directory "PythonPrograms". 
    
     import os
     
     def new_directory(directory, filename):
     
       # Before creating a new directory, check to see if it already exists
    
       if os.path.isdir(directory) == False:
     
       os.mkdir(directory)
     
       # Create the new file inside of the new directory
     
       os.chdir(directory)
     
       with open (filename,"w") as file:
     
        pass
     
     # Return the list of files in the new directory
     
        return os.listdir()
     
     print(new_directory("PythonPrograms", "script.py"))
>  XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
>  RunReset
> 
> <pre class="rc-ConsoleOutput">
> 
> ['script.py']
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Well done, you! Working with files and directories can be a
> little tricky, and you're getting the hang of it!
> 
> </pre>
> 
> 1 / 1 point
> 
>  3.Question 3
> 
> Which of the following methods from the os module will create a new directory? 
> 
>  path.isdir() 
> 
>  listdir() 
> 

      mkdir() 
> 
>  chdir() 
> 
> Check
> 
> Correct
> 
> Right on! os.mkdir() will create a new directory with the name provided as a string parameter.
> 
> 1 / 1 point
> 
>  4.Question 4
> 
> The file_date function creates a new file in the current working directory, checks the date that the file was modified, and returns just the date portion of the timestamp in the format of yyyy-mm-dd. Fill in the gaps to create a file called "newfile.txt" and check the date that it was modified. 
> 

> 

     import os
     
     import datetime
     
     def file_date(filename):
     
      # Create the file in the current directory
     
      os.mkdir(filename)
     
      timestamp = os.path.getmtime(filename)
     
      # Convert the timestamp into a readable format, then into a string
     
      date=datetime.datetime.fromtimestamp(timestamp)
     
      # Return just the date portion
     
      # Hint: how many characters are in “yyyy-mm-dd”?
     
      return ("{}-{}-{}".format(date.year,date.month,date.day))
     
     print(file_date("newfile.txt"))
     
     # Should be today's date in the format of yyyy-mm-dd
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

     2020-05-30
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Way to go! You remembered the commands to convert timestamps
> and format strings, to get the results that were requested.
> 
> </pre>
> 
> 1 / 1 point
> 
>  5.Question 5
> 
> The parent_directory function returns the name of the directory that's located just above the current working directory. Remember that '..' is a relative path alias that means "go up to the parent directory". Fill in the gaps to complete this function. 
> 
> 

     import os
     
     def parent_directory():
     
     # Create a relative path to the parent
     
     # of the current working directory
     
     os.chdir("..")
     
     relative_parent = os.getcwd()
     
    # Return the absolute path of the parent directory
     
     return relative_parent
     
     print(parent_directory())
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 
> /
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Excellent! You made all the right moves to print the path of
> the parent directory!
> 
> </pre>
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/1oBDy/practice-quiz-managing-files-directories/attempt?redirectToCover=true#Tunnel Vision Close
