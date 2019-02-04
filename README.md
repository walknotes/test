git clone https://github.com/walknotes/test;
cd test/;

#add folder or files, or edit something.

git add .;
git commit -m "Text Text";
git push;

#you will be asked for username and password, if you want to save it for the further.
git config credential.helper store;
git pull;
#then next time you push in thie folder, it won't prompt to ask for passwords. use  "git pull" again to change the password.

#to use emacs 
git config --global core.editor emacs -nw

#to change commit username and email address:
git config --global user.name "Your name";
git config --global user.email some@lklkajsd.com

#to check git status, what file be edited, added, deleted.
git status;





