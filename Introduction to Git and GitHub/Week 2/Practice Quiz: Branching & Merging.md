# Practice Quiz: Branching & Merging
> 
> Total points 5
> 
>  1.Question 1
> 
> When we merge two branches, one of two algorithms is used. If the branches have _diverged_, which algorithm is used?
> 
> 1 / 1 point 
> 

      three-way merge 
> 
>  fast-forward merge 
> 
>  merge conflict 
> 
>  orphan-creating merge 
> 
> Check
> 
> Correct
> 
> Excellent! A three-way-mergeoccurs when the two commits have diverged previously, and a new commit is created.
> 
>  2.Question 2
> 
> The following code snippet represents the result of a merge conflict. Edit the code to fix the conflict and keep the version represented by the current branch.
> 
> 1 / 1 point 
> 

     print("Keep me!")
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 
> Keep me!
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> You got it! No more conflicts here!
> 
> </pre>
> 
>  3.Question 3
> 
> What command would we use to throw away a merge, and start over?
> 
> 1 / 1 point 
> 
>  git checkout -b <branch> 
> 

      git merge --abort 
> 
>  git log --graph --oneline 
> 
>  git branch -D <name> 
> 
> Check
> 
> Correct
> 
> Right on! If there are merge conflicts, the --abort flag can be used to abort the merge action.
> 
>  4.Question 4
> 
> How do we display a summarized view of the commit history for a repo, showing one line per commit?
> 
> 1 / 1 point 
> 
>  git log --format=short 
> 
>  git branch -D <name> 
> 

      git log --graph --oneline 
> 
>  git checkout -b <branch> 
> 
> Check
> 
> Correct
> 
> Awesome! The commandgit log --graph --oneline shows a summarized view of the commit history for a repo.
> 
>  5.Question 5
> 
> The following script contains the result of a merge conflict. Edit the code to fix the conflict, so that both versions are included.
> 
> 1 / 1 point 
> 

     def main():
     
      print("Start of program>>>>>>>")
     
      print("End of program!")
     
     main()
> 
> XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
> 
> RunReset
> 
> <pre class="rc-ConsoleOutput">
> 
> Start of program>>>>>>>
> End of program!
> Start of program>>>>>>>
> End of program!
> None
> 
> </pre>
> 
> Check
> 
> Correct
> 
> <pre>
> 
> Great work! Now the code has both versions without any
> conflicts!
> 
> </pre>
>
> -- https://www.coursera.org/learn/introduction-git-github/quiz/wjd2M/practice-quiz-branching-merging/attempt?redirectToCover=true#Tunnel Vision Close
