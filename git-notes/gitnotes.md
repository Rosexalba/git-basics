# Creating repository & connecting to terminal


1. create new repository in git hub 
2. mkdir in terminal 
3. git init - initizalize branch making it (main)
4. git remote add origin git@github.com:Rosexalba/"repo name"
5. create file 
6. commit -m 
7. first push will be 'git push -u origin main'
   // after that 'git push' will do for future commits 


# Work flow 
 1. git add -A 
 2. git status 
 3. git commit -m 'leave a note on what youre committing'
 4. git push
--Commit often -- push when ready 

# Working with others [git branching]

1. git checkout -b Rose
// switched to a new branch 'Rose' [notmain]
commits will now stay on this branch 'Rose'

2. git checkout main // will take you back to the main branch 

// you can go back and forth and branches remain seperate at this point

3. git merge Rose // you are now merging your main branch with your individual branch 'Rose'
both files will now show up under main folder. <3
