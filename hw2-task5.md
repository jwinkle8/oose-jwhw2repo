#Task 5 - Git & Github
`git init`
`git add README.md`
`git commit -m "Create, add to local README" README.md`
-------------------------------------------
**On github.com...**
1. Clicked "New" for repository on account home page
2. Titled empty, remote repo "oose-jwhw2repo"
3. Clicked "Create repository"
------------------------------------------
`git remote add oose-jwhw2repo https://github.com/jwinkle8/oose-jwhw2repo.git`
`git push --set-upstream oose-jwhw2repo master`
-------------------------------------------
**On github.com...**
1. Clicked on README.md hyperlink on repo page.
2. Clicked "Edit this file"
3. Made changes to README.md
4. Added descriptive message for commit in designated box
5. Clicked "Commit changes" button on bottom of tab
-------------------------------------------
`git add README.md`
`git commit -m "Add 'Local' to README" README.md`
`git push`
`git fetch oose-jwhw2repo`
`git merge remotes/oose-jwhw2repo/master`
`git add README.md`
`git commit -m "Manage merge conflict; README.md reads README"`
-------------------------------------------
**On github.com...**
1. Clicked on "Issues" tab of oose-jwhw2repo
2. Clicked on "New Issue" button
3. Titled new issue "Making feature 1!" using designated box on new issue page
-------------------------------------------
`git branch feature1`
`git checkout feature1`
`git add FEATURE1.md`
`git commit -m "Add feature specs for feat1" FEATURE1.md` 
`git push --set-upstream oose-jwhw2repo feature1`
-------------------------------------------
**On github.com**
1. Clicked on "Compare & pull request"
2. Clicked on "Create pull request"
3. Clicked on "Merge pull request"
4. Clicked on "Confirm merge"
-------------------------------------------
`git checkout master`
`git pull`
