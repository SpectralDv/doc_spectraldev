1.Clon a repository
git clone https://github.com/...

2.Include to the repository
mkdir /forgit
cd /forgit
git init
git remote add origin https://github.com/...
git pull https://github.com/...

3.Add and check files for change in  repository
3.1.Check files for change to commit
git status
3.2.Add change to commit
git add .
3.3.Check files for change to commit
git status
3.4.Make commit with comment
git commit -m "comment"
git log
3.5.Upload to git
git branch -M 'main'
git push -u origin 'main'