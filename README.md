# how to do it:

## How to publish changes to the blog.

### Step 1: Run Git Push
 `git push`

### Step 2: Hugo build
 `./hugo.exe`

### Step 3: Create `gh-pages` branch from public folder
`./deploy.sh`

### Step 4: Push the local `gh-pages` branch to remote
`git push origin gh-pages:gh-pages --force`

