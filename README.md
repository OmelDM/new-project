# new-project

Start with creating a folder:
`mkdir new-project`

Go to a created folder:
`cd new-project`

Initialize Git repository:
`git init`

Rename branch to `main``:
`git branch main`

Create `README.md` file:
`touch README.md`

Add `README.md` file to tracked:
`git add README.md`

Write something in `README.md`

Add changes from `README.md` to staged:
`git add README.md`

Commit changes:
`git commit -m 'init`

Add repository to GitHub:
`git remote add origin git@github.com:OmelDM/new-project.git`

Push changes:
`git push origin main`

Create and checkout `development` branch:
`git checkout -b development main`

Update `README.md` with needed instructions

Add changes from `README.md` to staged:
`git add README.md`

Commit changes:
`git commit -m 'added instructions how to do Task`

Push changes:
`git push origin development`

Checkout `main` branch:
`git checkout main`

Merge `development` branch into `main` with merge commit:
`git merge --no-ff development`

Push changes:
`git push origin main`
