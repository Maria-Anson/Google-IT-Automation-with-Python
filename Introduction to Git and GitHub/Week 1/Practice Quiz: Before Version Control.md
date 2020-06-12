# Practice Quiz: Before Version Control
> 
> Total points 5
> 
>  1.Question 1
> 
> Your colleague sent you a patch called fix_names.patch, which fixes a config file called fix_names.conf. What command do you need to run to apply the patch to the config file?
> 
> 1 / 1 point 
> 
>  diff names.conf fix_names.conf 
> 
>  patch fix_names.conf names.conf 
> 

      patch fix_names.conf < fix_names.patch 
> 
>  diff names.conf_orig names.conf_fixed > fix_names.conf 
> 
> Check
> 
> Correct
> 
> Nice job! The patch command with the file to be patched, followed by the filename of the patch, will apply it.
> 
>  2.Question 2
> 
> You're helping a friend with a bug in a script called fix_permissions.py, which fixes the permissions of a bunch of files. To work on the file, you make a copy and call it fix_permissions_modified.py. What command do you need to run after solving the bug to send the patch to your friend?
> 
> 1 / 1 point 
> 

      diff fix_permissions.py fix_permissions_modified.py > fix_permissions.patch 
> 
>  patch fix_permissions.py < fix_permissions_modified.py 
> 
>  patch fix_permissions.py > fix_permissions.patch 
> 
>  diff fix_permissions.py fix_permissions.diff 
> 
> Check
> 
> Correct
> 
> Awesome! The diff command will allow us to compare and apply the differences between the files.
> 
>  3.Question 3
> 
> The _____ commandhighlights the words that changed in a file instead of working line by line.
> 
> 1 / 1 point 
> 
>  diff 
> 
>  diff -u 
> 

      vimdiff 
> 
>  patch 
> 
> Check
> 
> Correct
> 
> Right on! The vimdiff commandhighlights the words that changed in a file by color, in addition to working line by line.
> 
>  4.Question 4
> 
> How can we choose the return value our script returns when it finishes?
> 
> 1 / 1 point 
> 

      Using the exit command from the sys module 
> 
>  Use the patch command 
> 
>  Use the diff command 
> 
>  Use meld 
> 
> Check
> 
> Correct
> 
> Great work! A script can use sys.exit to finish processing and return the number passed as an argument as the script's return code.
> 
>  5.Question 5
> 
> In addition to the original files, what else do we need before we can use the patch command?
> 
> 1 / 1 point 
> 

      Diff file 
> 
>  exit command of the sys module 
> 
>  Version control 
> 
>  Full copy of the new files 
> 
> Check
> 
> Correct
> 
> Woohoo! We need to use the patch command with the diff file to apply new changes to the original file.
>
> -- https://www.coursera.org/learn/introduction-git-github/quiz/fNLY7/practice-quiz-before-version-control/attempt?redirectToCover=true#Tunnel Vision Close
