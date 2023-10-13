# how to do it:

## After Cloning the repository, pull down the submodules for the theme. 
`git submodule update --init --recursive`

## How to preview changes locally.

1. Turn on the hugo development server.
 `./hugo.exe server`

2. Visit the link that the hugo server outputs when it turns on.

## How to publish changes to the blog.

### Step 1: Run Git Push
 `git push`

### Step 2: Hugo build
 `./hugo.exe`

### Step 3: Create `gh-pages` branch from public folder
`./deploy.sh`

### Step 4: Push the local `gh-pages` branch to remote
`git push origin gh-pages:gh-pages --force`

