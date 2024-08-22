Task 1: Repository Setup
1. Create a GitHub Repository:
    Log in to your GitHub account.
    Create a new repository (e.g., "PLPBasicGitAssignment").

Task 2: Local Setup
2. Set up a Local Folder:
    Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").
    Open a terminal or command prompt and navigate to the created folder.
3. Initialize a Git Repository:
    Initialize a new Git repository in your local folder.
4. Connect to GitHub:
    Link your local repository to the GitHub repository.
        git remote add origin <repository-url>
Task 3: Making Changes
5. Create a File:
    Create a new text file (e.g., hello.txt) in your local folder.
    Add a simple text message (e.g., "Hello, Git!").
6. Commit Changes:
    Stage the changes: git add hello.txt
    Commit the changes: git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub
7. Push to GitHub:
    Push the committed changes to your GitHub repository: git push -u origin main
Task 5: Verification
8. Verify on GitHub:
    Visit your GitHub repository in a web browser and confirm that the hello.txt file and commit message are visible.