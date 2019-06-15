# Git Good

## What is Git?
Git is a "version control system". It tells you what files changed, who changed them and why they changed it.

GitHub is a website for *hosting* projects that *use* git.

## Git Terminology
`Repository`: A project  
`Commit`: A checkpoint. You can see what files were changed and a little message written by the person who changed them.  
`Pull`: Download the project to your PC  
`Push`: Upload the project  

`Branch`: <TODO> The default one is the master branch.


<br>

It looks kinda like this:
![Imgur](https://i.imgur.com/c4skNTu.png?1)

[**Here is a more in depth version**](http://patrickzahnd.ch/uploads/git-transport-v1.png)  

<br>

### Commits and Branches  

Here is a nice guide: http://patrickzahnd.ch/blog.html#gitflow

## [GitHub](https://github.com/)
Make sure that you have a GitHub account

## [GitKraken](https://www.gitkraken.com/)

### Setting it up
1. Download it  
2. Install it
3. Sign in using your GitHub account

### Setting up the ssh key
1. Open GitKraken
2. `File`
3. `Preferences` (Ctrl+,)
4. `Authentication`
5. Switch to the `General` tab
6. Press on the green `Generate` button (Generate new Private/Public key)
7. Copy your public key
![Imgur](https://i.imgur.com/IfdtTud.png)

8. Go to https://github.com/settings/keys 
9. Press on the green `New SSH key` button
10. Give it a title and paste the SSH key





### Cloning a repository

1. Get the **ssh** link to the remote repository:
   1. Go to the repository on GitHub
   2. Press on `Clone or Download` (Green button)
   3. `Use SSH`
   4. Copy that link
2. Open GitKraken
3. Press on `File` in the top left corner
4. `Clone Repo` (Ctrl+N)
5. Paste the link
6. `Clone the repo!`

### The Interface
![Imgur](https://i.imgur.com/6VU34r0.png)
