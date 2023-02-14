# GitPracticals

Created branch cool_feature.
Add 2 files cool_feature1.txt and cool_feature2.txt in it.
Commited this 2 files.
Pushed this 2 files to cool_feature branch.
Created branch developer.
Add 2 files developer1.txt and developer2.txt in it.
Commited this 2 files in developer branch.

git Checkout  cool_feature branch.
git rebase  developer

These 2 commands rebase developer branch on tip of cool_feature branch.

Then 

git Checkout developer
git rebase cool_feature

By these 2 commands rebase cool_feature branch and developer branch point to cool_feature1.txt.

git push origin developer 

push all the commits of cool_feature branch and developer branch to github.com developer branch.
