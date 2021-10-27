# how to do it:

### Step 1: Hugo build
 `./hugo.exe`

### Step 2: Create `gh-pages` branch from public folder
`./deploy.sh`

### Step 3: Push the local `gh-pages` branch to remote
`git push origin gh-pages:gh-pages --force`