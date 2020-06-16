# Practice Quiz: Advanced Git Interaction
> 
> Total points 5
> 
>  1.Question 1
> 
> Which of the following commands is NOT an example of a method for comparing or reviewing the changes made to a file?
> 
> 1 / 1 point 
> 
>  git log -p 
> 
>  git diff --staged 
> 
>  git add -p 
> 

      git mv 
> 
> Check
> 
> Correct
> 
> Nice job! git mv won't give you any information on changes. Instead, it is used to move or rename a file or directory in Git.
> 
>  2.Question 2
> 
> What is the gitignore file?
> 
> 1 / 1 point 
> 
>  A file containing a list of commands that Git will ignore. 
> 
>  A file the user is intended to ignore. 
> 
>  A file listing uncommitted changes. 
> 

      A file containing a list of files or filename patterns for Git to skip for the current repo. 
> 
> Check
> 
> Correct
> 
> Awesome! The gitignore file is a text file that tells Git which files or folders to ignore in a project.
> 
>  3.Question 3
> 
> What kind of file will the command git commit -a not commit?
> 
> 1 / 1 point 
> 
>  Tracked files 
> 

      New files 
> 
>  Old files 
> 
>  Staged files 
> 
> Check
> 
> Correct
> 
> Right on! Files that are new and untracked will not be committed before being added.
> 
>  4.Question 4
> 
> What does HEAD represent in Git?
> 
> 1 / 1 point 
> 
>  The subject line of a commit message 
> 
>  The top portion of a commit 
> 

      The currently checked-out snapshot of your project 
> 
>  The first commit of your project 
> 
> Check
> 
> Correct
> 
> Great work! In all cases, HEAD is used to indicate what the currently checked-out snapshot is.
> 
>  5.Question 5
> 
> If we want to show some stats about the changes in a commit, like which files were changed and how many lines were added or removed, what flag should we add to git log?
> 
> 1 / 1 point 
> 

      --stat 
> 
>  --patch 
> 
>  -2 
> 
>  --pretty 
> 
> Check
> 
> Correct
> 
> Excellent! This will cause git log to show some stats about the changes in the commit, like which files were changed and how many lines were added or removed.
>
> -- https://www.coursera.org/learn/introduction-git-github/quiz/zfvVZ/practice-quiz-advanced-git-interaction/attempt?redirectToCover=true#Tunnel Vision Close
