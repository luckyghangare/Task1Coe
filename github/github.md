# Task1coe

<!-- Github Commands that we learned are:  -->

1)   git config --global user.name "Your Name"
2)   git config --global user.email "your@email.com"
3)   git clone LINK
4)   git init
5)   git status
6)   git add filename
7)   git add .
8)   git commit -m "Your commit message"
9)   git remote add origin LINK
10)  git push origin main
11)  git checkout branch-name
12)  git switch branch-name


<!-- How to add a commit in a friend's project -->

## How to Contribute to a Friend's GitHub Project

### Step 1: Fork the Repository
- Go to your friend's GitHub repository
- Click the **Fork** button (top-right corner)
- This creates a copy of the project under your GitHub account

### Step 2: Clone Your Fork Locally
```
git clone LINK_OF_YOUR_FORKED_REPO
cd FOLDER_NAME
```

### Step 3: Add the Original Repo as Upstream (optional but recommended)
```
git remote add upstream LINK_OF_FRIENDS_ORIGINAL_REPO
```

### Step 4: Create a New Branch for Your Changes
```
git checkout -b your-branch-name
```

### Step 5: Make Your Changes
- Edit or add files as needed

### Step 6: Stage and Commit Your Changes
```
git add .
git commit -m "Describe what you changed"
```

### Step 7: Push Your Branch to Your Fork
```
git push origin your-branch-name
```

### Step 8: Open a Pull Request
- Go to your forked repo on GitHub
- Click **Compare & pull request**
- Add a title and description, then click **Create pull request**
- Your friend can review and merge your changes into their project
