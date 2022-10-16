## The coolest Scientific Programming Exercise ever
First exercise with GitHub für SP in MBDS at URV

### Git commands

#### git clone git@github.com:lea-rothoerl/scientificprogramming_ex.git
Uses the ssh interface of GitHub to clone the online repository into a local git repository

#### git branch new_branch
Within the local repository creates a new branch 

#### git checkout new_branch
Cheksout the newly created branch, so that any changes made, will be made to that branch instead of the main branch

#### git add local_file
Stages the changes made to local_file or if newly created, adds that file

#### git commit -m "this is my first commit"
Commits the staged changes to the new_branch with a commit message. 

#### git push origin new_branch
The committed changes get pushed to the original remote repository which was cloned originally. 
If new_branch already exists, the changes get made to that branch, else it is created for that purpose

### Merge
We merged the different branches through the GitHub website interface using a pull request.
