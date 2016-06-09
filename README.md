# Tutorial-Git
how to upload files to git for beginners (Windows)

INSTALL
1. Download here git-scm.com
2. During installation, I choose Run Git from Windows Commpand Prompt. Other option, I just let it be
3. Done

UPLOAD FILES
1. Create new repository in your Git - click Create Repository
2. Right click the file/folder that want to upload - choose Git Bash here
3. In command window, type these and ENTER
  a) git init
  b) git add .
  c) git commmit -m "Your message here"
  d) git remote add origin https://github.com/your username/your repo created in step 1.git
  e) git pull origin master
    EXTRA: if got a window asking for message, refer here http://stackoverflow.com/questions/14046122/github-locks-up-mac-terminal-when-using-pull-command/37718057#37718057
  f) git push origin master

DONE!
