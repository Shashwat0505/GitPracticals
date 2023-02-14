# GitPracticals

Created branch new_cherry_pick.
Checkout to new_cherry_pick branch.
Created file test1.txt with command:- touch test1.txt.
Added test1.txt to staging area with command:- git add .
Applied commit with message 'test1.txt file added'.
Similarly test2.txt file created and commited with message 'test2.txt file added'.
Pushed this 2 commits to new_cherry_pick branch with command:-git push origin new_cherry_pick.
Applied git log command to find id of commit in which test1.txt file added.
Copy that id.
Checkout to master branch.
To apply commit of test1.txt file to master branch command:-git cherry-pick <commit id>.
test1.txt file added to master branch.
