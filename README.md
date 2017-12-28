# How-To-Work-With-Github

open cmd and go to directory where you want to download repository and follow as below

1) clone git to your machine below code

git clone https://github.com/nishit-manjarawala/newGittest.git

2) put your all files into repository 

3) run new command : git status

This command show file status of our repository

4) run new command as below to add files to repository

git add Filename

if want to add all file use '.'

5) if you have not set up your git global email and name then set it as below else skip this point

git config --global user.email "manjarawalanishit@gmail.com"

git config --global user.name "Nishit"


6) Now Commit your work with message as below

git commit -m "first file commit"

-m is use for set message with for commit

on commit github ask for email and password

7) after successfully commit still file not updated on github. for update on github run command as below.

git push

8) if you want to get new or update file from github to your local system run command as below

git pull
