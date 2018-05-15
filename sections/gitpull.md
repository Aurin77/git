[<<< Previous](gitaction.md) | [Next >>>](gitchallenge.md)

# Making a copy of a GitHub repo to work on locally
## Cloning

A **clone** is a local copy of a repository.  

`git clone [URL of your GitHub repo]`

This clones a remote repository to your computer so you can customize it to your taste. 

**First, make sure you are out of GitPractice before you clone.** Let's navigate to the Desktop. 

Clone the [repo for this workshop](https://github.com/DHRI-Curriculum/git) so you can have a copy for yourself!

`git clone https://github.com/DHRI-Curriculum/git`

In the future, you can use the GUI on GitHub (buttons on the web page) to do the same thing. There should be a "clone or download" button near the top right of each repository. 

## Pulling

If you receive an error notification that you are unable to push changes to your GitHub repo from your local repo, it often means that changes have been made to your GitHub repo that have not yet been logged locally. You'll have to pull the repo, using `git pull [URL of your GitHub repo]` then merge the changes by using `git commit -u origin master` in order to return to smoother sailing with your `git push` commands. 


[<<< Previous](gitaction.md) | [Next >>>](gitchallenge.md)
