git clone https://github.com/walknotes/test;
cd test/;

#make some change.
#add somefile.

git add . #add all files in this folder.

#then you must commit, before push.
git commit -m "Text Text";
git push;

#you will be asked for username and password, if you want to save it for the further.
git config credential.helper store;
git pull;

#then next time you push in thie folder, it won't prompt to ask for passwords.

#to use emacs 
git config --global core.editor emacs -nw

#to change commit username and email address:
git config --global user.name "Your name";
git config --global user.email some@lklkajsd.com

#to check git status:

git status;





