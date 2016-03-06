# octocat
# Learning Git from Code Academy
git add 'filename' # to Staging Area
git commit - m "message"
git remote add origin "https://github.com/gabrielsg/SomeRepository.git"  
#create SomeRepository.git
git push - u origin master 
# prompt for username and password; name of remote is origin; default local branch is mater; -u remembers parameters

# add 2nd file
git add 'filename2'
git commit -m "I'm adding 2nd file"
git push

#check changes
git pull origin master

#check difference
git diff HEAD 
# HEAD points to recent changes
