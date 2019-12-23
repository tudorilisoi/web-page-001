# web-page-001

```
echo "# web-page-001" >> README.md #create a file
git init #init a git repo if not already present
git add README.md # stage this file for commit
git commit -m "first commit" # commit whatever was staged

# do this one time only, it sets your github repo as a remote named 'origin'
git remote add origin git@github.com:tudorilisoi/web-page-001.git 

git push -u origin master #push your latest commits to GitHub

```

# Git  workflow (assumes a remote repository, i.e. working on a team):

1. git pull
2. work on the project and `git commit`
3. git push
4. repeat

### Happy holidays!
