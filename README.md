# test_github
This repo was created to support my github workshops as a way to get you to start using github. Follow these steps to practice editing code collaboratively after [creating a github login](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github) and downloading [github desktop](https://desktop.github.com/download/).

## First Steps!
1. **Clone this repo onto your desktop**: Open github desktop and login > click "clone repository from the internet" > find this repo, "test_github" > click "clone." This repo will now show as your current repository, and there will be a folder titled GitHub created on your desktop, which will house all repos from here on out.
2. **Fetch code**: Click "fetch origin" to refresh and make sure your repo is up to date.
3. **Open File**: Now, in the GitHub folder on your desktop, find the subfolder titled test_github and open it, you will see a R script titled "test_script", open that
4. **Practice pushing**: Have Person 1 make an edit (can just be a word, or ! or >.<), then save like you regularly would, then close the file. In github desktop, you should see 1 changed file and below, a summary bubble and a blue button "commit to main." Edit the summary bubble if you want, then click commit to main, then click the blue "push origin" button that appears on the right. Commit to main saves your changes to your local repo (labeled with whatever you put in summary), and push origin saves your changest to the remote repo (what everyone else will see, and pull).
5. **Practice pulling**: Now, in github desktop, Person 2 should click "fetch origin" which is a refresh button and will grab Person 1's commit. There should be a blue "pull origin" button that pops up on the right side, this shows that there have been changes made to the script that are not currently shown on Person 2's device. Click pull origin, then open the test_script file, and you should see the changes Person 1 made.
6. **Repeat**: Person 2 should now repeat step 4, after which Person 1 can repeat step 5. Now, both of you should know how to push and pull! 

## The daily flow for GitHub using GitHub Desktop
1) Pull latest changes (click "Fetch origin" → "Pull")
2) Create/switch to your branch (if neeeded)
3) Open code and make changes
4) GitHub Desktop will detect the changes — write a commit message in the bottom left and click "Commit to branch-name"
5) Click "Push origin" to push to GitHub
6) Open a Pull Request by clicking "Create Pull Request" — it'll open GitHub in your browser

## Ground rules for contributing to a repo
- As a contributor, *clone* a repo onto your personal device, **do not fork it**
- Create logical subfolders/scripts for your work and name them clearly
- Before beginning work, always "fetch/pull origin" through GitHub Desktop to reduce merge conflicts
- At a minimum, you should be pushing your changes to our repo **once a day**
- If you need to use branches (you may not): 1) The main branch should always be deployable - create branches for specific tasks, 2) only one person should be merging completed branches into the main branch, and 3) once branches are merged, delete branches to keep the repo tidy

### ONLY IF NEEDED: How to create a new branch with GitHub Desktop
1) Click the "Current Branch" dropdown at the top
2) Click "New Branch"
3) Type your branch name (e.g. feature/objective-yourname)
4) Click "Create Branch"
5) Then publish it to GitHub, click "Publish Branch" so your group can see it
- Reminder: Make sure you pull main first before creating your branch so you start with the latest version including the folder structure
5) Click "Commit to branch-name"
6) Click "Push Origin" at the top right to send it to GitHub
