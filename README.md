git config --global user.name "lark"
git config --global user.email "brianireri88@gmail.com"
git config --global push.default matching
git config --global alias.co checkout
git init
git add .
git commit -am 'first commit'
create repository
git remote add origin https://github.com/IAMLARK/new.git
git branch -M main
git push -u origin main
 
git checkout main (switch to main branch/switching btn branches )
git pull origin main (update latest code)
git checkout -b homepage (creates new branch called homepage)
new pull request -> select branch -> add description

***if there are new changes from the main branch***
git checkout main (Make sure you're on the main branch)
git pull origin main (Fetch and merge the latest changes from the remote main)
git checkout your-feature-branch (Switch back to your branch)
git merge main (Merge the latest changes from main into your feature branch)

***if you want to clone from a certain point of commit
git clone https://github.com/username/repo.git
cd repo
git checkout <commit_hash> (Go to your repo on GitHub → Click "Commits" tab.Locate the 30th commit from the top (oldest-first = bottom of the list).Copy the commit SHA hash (looks like a1b2c3d...).)


