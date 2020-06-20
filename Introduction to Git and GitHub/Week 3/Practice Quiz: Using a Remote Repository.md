# Practice Quiz: Using a Remote Repository
> 
> Total points 5
> 
>  1.Question 1
> 
> In order to get the contents of a remote branch without automatically merging, which of these commands should we use?
> 
> 1 / 1 point 
> 
>  git pull 
> 

      git remote update 
> 
>  git checkout 
> 
>  git log -p -1 
> 
> Check
> 
> Correct
> 
> You got it! git remote update will fetch the contents of all remote branches and allow us to merge the contents ourselves.
> 
>  2.Question 2
> 
> If we need to find more information about a remote branch, which command will help us?
> 
> 1 / 1 point 
> 
>  git fetch 
> 
>  git checkout 
> 
>  git remote update 
> 

      git remote show origin 
> 
> Check
> 
> Correct
> 
> Right on! If you want to see more information about a particular remote branch, you can use the git remote show command. Don't forget the commit ID!
> 
>  3.Question 3
> 
> What command will download remote branches from remote repositories without merging the content with your current workspace automatically?
> 
> 1 / 1 point 
> 
>  git checkout 
> 
>  git pull 
> 

      git fetch 
> 
>  git remote update 
> 
> Check
> 
> Correct
> 
> Nice work! git fetch will download remote updates, such as objects and refs, from the remote branch.
> 
>  4.Question 4
> 
> What type of merge creates a new merge commit?
> 
> 1 / 1 point 
> 
>  Fast-forward merge 
> 
>  Implicit merge 
> 

      Explicit merge 
> 
>  Squash on merge 
> 
> Check
> 
> Correct
> 
> Woohoo! An explicit merge creates a new merge commit. This alters the commit history and explicitly shows where a merge was executed.
> 
>  5.Question 5
> 
> What method of getting remote contents will automatically merge the remote branch with the current local branch?
> 
> 1 / 1 point 
> 
>  git fetch 
> 
>  git checkout 
> 
>  git remote update 
> 

      git pull 
> 
> Check
> 
> Correct
> 
> Great job! git pull automatically merges the remote branch with the current branch.
>
> -- https://www.coursera.org/learn/introduction-git-github/quiz/AcApM/practice-quiz-using-a-remote-repository/attempt?redirectToCover=true#Tunnel Vision Close
