# Practice Quiz: Reading & Writing CSV Files
> 
> Total points 5
> 
>  1.Question 1
> 
> We're working with a list of flowers and some information about each one. The create_file function writes this information to a CSV file. The contents_of_file function reads this file into records and returns the information in a nicely formatted block. Fill in the gaps of the contents_of_file function to turn the data in the CSV file into a dictionary using DictReader. 

     import os

     import csv

     # Create a file with data in it

     def create_file(filename):

      with open(filename, "w") as file:

      file.write("name,color,type\n")

      file.write("carnation,pink,annual\n")

      file.write("daffodil,yellow,perennial\n")

      file.write("iris,blue,perennial\n")

      file.write("poinsettia,red,perennial\n")

      file.write("sunflower,yellow,annual\n")

     # Read the file contents and format the information about each row

     def contents_of_file(filename):

      return_string = ""

      # Call the function to create the file

      create_file(filename)

      # Open the file

      with open(filename) as file:

        # Read the rows of the file into a dictionary

        dic=csv.DictReader(file)

        # Process each item of the dictionary

        for row in dic :

          return_string += "a {} {} is {}\n".format(row["color"], row["name"],row["type"])

      return return_string

     #Call the function

     print(contents_of_file("flowers.csv"))
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

     a pink carnation is annual
     a yellow daffodil is perennial
     a blue iris is perennial
     a red poinsettia is perennial
     a yellow sunflower is annual
> 
> </pre>
> 
> Check
> 
> Correct
> 
> </pre>
> 
> 1 / 1 point
> 
>  2.Question 2
> 
> Usig the CSV file of flowers again, fill in the gaps of the contents_of_file function to process the data without turning it into a dictionary. How do you skip over the header record with the field names? 
> 

     import os
     
     import csv
     
     # Create a file with data in it
     
     def create_file(filename):
     
      with open(filename, "w") as file:
     
        file.write("name,color,type\n")
    
        file.write("carnation,pink,annual\n")
    
        file.write("daffodil,yellow,perennial\n")
     
        file.write("iris,blue,perennial\n")
     
        file.write("poinsettia,red,perennial\n")
    
        file.write("sunflower,yellow,annual\n")
    
     # Read the file contents and format the information about each row
     
     def contents_of_file(filename):
     
      return_string = ""
     
      # Call the function to create the file
     
      create_file(filename)
     
      # Open the file
     
      with open(filename) as file:
     
        # Read the rows of the file
     
        rows = csv.reader(file)
     
        # Process each row
     
        for row in rows:
     
          name,color,type = row
     
          # Format the return string for data rows only
     
          if name!='name':
     
            return_string += "a {} {} is {}\n".format(color,name,type)
     
      return return_string
     
     #Call the function
     
     print(contents_of_file("flowers.csv"))
    > 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 

     a pink carnation is annual
     a yellow daffodil is perennial
     a blue iris is perennial
     a red poinsettia is perennial
     a yellow sunflower is annual
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> You nailed it! Everything's coming up roses (pardon the
> pun!)
> 
> </pre>
> 
> 1 / 1 point
> 
>  3.Question 3
> 
> In order to use the writerows() function of DictWriter() to write a list of dictionaries to each line of a CSV file, what steps should we take? (Check all that apply) 
> 

      Create an instance of the DictWriter() class 
> 
> Check
> 
> Correct
> 
> Excellent! We have to create a DictWriter() object instance to work with, and pass to it the fieldnames parameter defined as a list of keys.
> 

      Write the fieldnames parameter into the first row using writeheader() 
> 
> Check
> 
> Correct
> 
> Nice work! The non-optional fieldnames parameter list values should be written to the first row.
> 

      Open the csv file using _with open_ 
> 
> Check
> 
> Correct
> 
> Good call! The CSV file has to be open before we can write to it.
> 
>  Import the OS module 
> 
> 1 / 1 point
> 
>  4.Question 4
> 
> Which of the following is true about unpacking values into variables when reading rows of a CSV file? (Check all that apply) 
> 
>  We need the same amount of variables as there are columns of data in the CSV 
> 
> Check
> 
> Correct
> 
> Awesome! We need to have the exact same amount of variables on the left side of the equals sign as the length of the sequence on the right side when unpacking rows into individual variables.
> 

      Rows can be read using both csv.reader and csv.DictReader 
> 
> Check
> 
> Correct
> 
> Right on! Although they read the CSV rows into different datatypes, both csv.reader or csv.DictReader can be used to parse CSV files.
> 

      An instance of the reader class must be created first 
> 
> Check
> 
> Correct
> 
> Nice job! We have to create an instance of the reader class we are using before we can parse the CSV file.
> 
>  The CSV file does not have to be explicitly opened 
> 
> 1 / 1 point
> 
>  5.Question 5
> 
> If we are analyzing a file's contents to correctly structure its data, what action are we performing on the file? 
> 
>  Writing 
> 
>  Appending 
> 

      Parsing 
> 
>  Reading 
> 
> Check
> 
> Correct
> 
> Great work! Parsing a file means analyzing its contents to correctly structure the data. As long as we know what the data is, we can organize it in a way our script can use effectively.
>
> -- https://www.coursera.org/learn/python-operating-system/quiz/t1sYe/practice-quiz-reading-writing-csv-files/attempt?redirectToCover=true#Tunnel Vision Close
