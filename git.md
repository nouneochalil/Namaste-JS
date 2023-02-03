git config --global user.name "noureen"
git config --global user.email "email"
git init
git add Readme.md
git commit -m "created Readme.md file"   //add a message
git remote add  host https://github.com/nouneochalil/Namaste-JS.git 

<!-- connecting the remote file with your repo. only once you need to use this command.-->
git push host master
whenever you add a new file you can use below 2 commands to add repo.
git add filename.
git commit -m "message"  