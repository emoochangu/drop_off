# Drop Off Demo

We will **Push** your Project Proposal to your GitHub repository.

You can do this in two different ways:

1. Using the Terminal

2. Using the GitHub website

## Step 0 for both methods — Make Sure You Have a Repository!

You should already have:

- A GitHub account

- A repository created (for example: data271-project)

If not:

Go to github.com

Click New Repository

Name it something like:

```
data271-project
```

## Method 1 — Using the Terminal

This method is how developers normally work.


### Step 1 — Clone Your Repository (Only Do This Once)

Open your terminal (or Jupyter terminal).

Run:
```
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
```

Then move into the folder:
```
cd data271-project
```

### Step 2 — Add Your Project Proposal File

Move your proposal file into this folder.

Example file names:

```
project_proposal.md
project_proposal.pdf
project_proposal.ipynb
```


You can:

- Drag and drop into the folder
- Or move it using terminal
  
### Step 3 — Check Git Status

Run:

```
git status
```


You should see your file listed under:

```
Untracked files:
```

This means Git sees the file but is not tracking it yet.

### Step 4 — Stage the File

Tell Git you want to include the file in your next commit:

```
git add project_proposal.md
```

Or add everything:

```
git add .
```

Check again:

```
git status
```

Now it should say:

```
Changes to be committed:
```

### Step 5 — Commit

Create a save point with a message:

```
git commit -m "Add project proposal"
```

Think of a commit as a snapshot in time.

### Step 6 — Push to GitHub

Now send your commit to GitHub:

```
git push
```

If prompted:

Enter your GitHub username

Use your Personal Access Token (PAT) as your password

### Step 7 — Verify

Go to GitHub in your browser.

Refresh your repository page.

You should see your file there 🎉





## Method 2 — Using the GitHub Website

This method is simpler but less powerful.

### Step 1 — Open Your Repository

Go to:

```
https://github.com/YOUR-USERNAME/YOUR-REPO-NAME
```

### Step 2 — Click “Add file”

Click:

```
Add file → Upload files
```

### Step 3 — Drag Your File

Drag your project proposal file into the upload area.

Wait for it to finish loading.

### Step 4 — Commit Changes

At the bottom of the page:

Add a commit message: ```Add project proposal```

Click:

```
Commit changes
```

