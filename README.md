# 3CHIF Git Good

## What is Git?
> Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. -- Wikipedia


Git is a magical piece of software that allows you to work "together". (Version control system)  
The code is hosted on a server. (**GitHub** or **GitLab**)  
You have a copy of everything (**GitKraken** deals with that copy) 
After you change a bit of stuff, you have to **commit** it with GitHub for Desktop. (That's a backup/snapshot)  
Then, when you are happy with everything, you **push** it to the server. (Upload)  
After you **pushed** your code to the server, everybody else has to **pull** it. (Download)

<br>

It looks kinda like this:
![Imgur](https://i.imgur.com/c4skNTu.png?1)

[**Here is a more in depth version**](http://patrickzahnd.ch/uploads/git-transport-v1.png)  

<br>

### Commits and Branches  

Here is a nice guide: http://patrickzahnd.ch/blog.html#gitflow


<br>
<h2> <a href="https://www.gitkraken.com/"> GitKraken </a> </h2>

### Setting it up (Required)
1. Download it  
2. Install it
3. Sign in using your GitHub account OR create a GitKraken account

### Setting up the ssh key (Required)
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
3. Press on `File`
4. `Clone Repo` (Ctrl+N)
5. Paste the link
6. ???
7. Profit

### The Interface
![Imgur](https://i.imgur.com/6VU34r0.png)
