<h1> Notes of Data Engineering Track in Python from Data Camp</h1>

<h2> Command lines from git introduction lecture</h2>
<h3> Create a new repository in your local machine</h3>
<li> 1. echo "DE_Study_Notes" >> README.md</li>
<li> 2. git init</li>
<li> 3. git branch -m main</li>
<li> 4. git remote add origin https://github.com/pillow121/DE_Study.git</li>
<li> 5. git push -u origin main</li>

<h4><li>Staging ---> git stage filename</li>
    <li>Commiting ---> git commit -m "message"</li>
    <li>git status</li>
</h4>

<h2> Command lines from Intermediate git lecture</h2>
<h3>Branches</h3>

<li> switching  ---> git switch -c branch_name</li>
<li> checking  ---> git branch</li>
<li> comparing  ---> git diff branch_1 branch_2</li>
<li> rename ---> git branch -m old_branchName new_branchName</li>
<li> delete ---> <ul>git branch -d branch_name (it will show error if you haven't merged to main)
                 </ul>
                 <ul>use 'git branch -D branch_name' to avoid error</ul>
</li>
<li>merge ---> <ul>merge to main ---> git merge source</ul>
                <ul> if you are in main, git merge 'branch_name' (merge 'branch_name' to main)</ul>
                <ul> or if you are in another branch, git merge 'branch_name' main</ul>
</li>

