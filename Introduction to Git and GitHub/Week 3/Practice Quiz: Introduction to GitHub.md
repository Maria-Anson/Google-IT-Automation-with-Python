# Practice Quiz: Introduction to GitHub
> 
> Total points 4
> 
>  1.Question 1
> 
> When we want to update our local repository to reflect changes made in the remote repository, which command would we use?
> 
> 1 / 1 point 
> 
>  git clone <URL> 
> 
>  git push 
> 

      git pull 
> 
>  git commit -a -m 
> 
> Check
> 
> Correct
> 
> Right on! git pull updates the local repository by applying changes made in the remote repository.
> 
>  2.Question 2
> 
> git config --global credential.helper cache allows us to configure the credential helper, which is used for ...what?
> 
> 1 / 1 point 
> 
>  Troubleshooting the login process 
> 
>  Dynamically suggesting commit messages 
> 
>  Allowing configuration of automatic repository pulling 
> 

      Allowing automated login to GitHub 
> 
> Check
> 
> Correct
> 
> Nice work! By configuring the credential helper, we can avoid having to type in our username and password repeatedly.
> 
>  3.Question 3
> 
> Name two ways to avoid having to enter our password when retrieving and when pushing changes to the repo. (Check all that apply)
> 
> 1 / 1 point 
> 
>  Implement a post-receive hook 
> 

      Use a credential helper 
> 
> Check
> 
> Correct
> 
> Awesome! The credential helper caches our credentials for a time window, so that we don't need to enter our password with every interaction.
> 

      Create an SSH key-pair 
> 
> Check
> 
> Correct
> 
> Great job! We can create an SSH key-pair and store the public key in our profile, so that GitHub recognizes our computer.
> 
>  Use the git commit -a -m command. 
> 
>  4.Question 4
> 
> Before we have a local copy of a commit, we should download one using which command?
> 
> 1 / 1 point 
> 
>  git commit -a -m 
> 
>  git push 
> 
>  git pull 
> 

      git clone <URL> 
> 
> Check
> 
> Correct
> 
> Woohoo!. If the repository already exists locally, this may raise an error.
>
> -- https://www.coursera.org/learn/introduction-git-github/quiz/YDLD3/practice-quiz-introduction-to-github/attempt?redirectToCover=true#Tunnel Vision Close
