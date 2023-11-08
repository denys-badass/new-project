# New Project

This repository is for the 'new-project' and is used to manage its source code and development process. It contains the main branch and a development branch.

## Step 1: Create a New GitHub Repository

1. Open your web browser and go to GitHub (https://github.com).

2. Log in to your GitHub account.

3. Click the '+' sign in the upper-right corner and select "New repository."

4. Fill out the repository information:
   - Repository name: `new-project`
   - Choose visibility public

5. Click "Create repository" to create your new repository.

## Step 2: Clone the Repository

1. Open your terminal.

2. Clone the newly created repository to your local machine. Replace `<repository_url>` with your repository URL:

    ```bash
    git clone <repository_url>
    ```

## Step 3: Create README.md, add file to staging area and make first commit

1. Switch to the repository directory:

    ```bash
    cd new-project
    ```

2. Create file README.md

    ```bash
    echo "# New Project" > README.md
    ```

3. Add file to staging area

    ```bash
    git add README.md
    ```

4. Make initial commit

    ```bash
    git commit -m "init"
    ```

## Step 3: Create a Development Branch, and working with README.md file


1. Create a new branch for your development work.

    ```
    git checkout -b development
    ```

2. Add the instructions to the README.md file and make a comit.

    ```bash
    git commit -am "Change README"
    ```

## Step 4: Merging into the Main Branch

1. Switch back to the main branch:

    ```bash
    git checkout main
    ```

2. Merge your development branch into the main branch:

    ```bash
    git merge development
    ```
3. Push your changes to the GitHub repository:

    ```bash
    git push origin main
    ```

