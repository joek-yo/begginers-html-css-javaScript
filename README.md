## README

## Git, GitHub, And Open Source Exploration Process

### Cloning and Forking

1. Cloned the repository:
    ```
    git clone https://github.com/begginers-html-css-javaScript.git
    cd public-apis
    ```

2. Forked the repository on GitHub and cloned the forked repository:
    ```
    git clone https://github.com/joek-yo/begginers-html-css-javaScript.git
    cd public-apis
    ```

### Managing Branches

1. Created and switched to a new branch:
    ```
    git checkout -b feature-update
    ```

2. Made changes to `index.html` and committed:
    ```
    git add .
    git commit -m "updates"
    ```

3. Merged changes from `feature-update` branch into `main`:
    ```
    git checkout main
    git merge feature-update
    ```

### Handling Conflicts

1. Created a conflict by modifying `index.html` on GitHub and pulling changes:
    ```
    git pull
    ```

2. Resolved conflict and merged:
    ```
    git checkout -b resolve-conflict
    git add .
    git commit -m "Resolve conflict in newfile.txt"
    git checkout main
    git merge resolve-conflict
    ```

### GitHub Pages

1. Created `home.html` for GitHub Pages and enabled GitHub Pages in repository settings.

2. Verified the GitHub Pages URL.

### Open Source Exploration

1. Explored the [public-apis](https://github.com/public-apis/public-apis) project.

2. Opened an issue suggesting an improvement.

### Repository Link

- [Forked Repository](https://github.com/YOUR-USERNAME/public-apis)

### Open Source Project

- [public-apis](https://github.com/public-apis/public-apis)
