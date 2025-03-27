Steps to Upload Large Files to Github

1️⃣ Initialize a Git repository:
git init

2️⃣ Connect to a remote GitHub repository:
git remote add origin <github-link>

3️⃣ Set up user details (if not configured globally):
git config user.name "<your-name>"
git config user.email "<your-email>"

4️⃣ Install Git LFS (if not already installed):
git lfs install

5️⃣ Specify file types to track with Git LFS:
git lfs track "*.zip"  # Modify as needed (e.g., "*.mp4", "*.rar")
💡 To track all files, use:
git lfs track "*"

6️⃣ Stage all files for commit:
git add .

7️⃣ Commit changes with a message:
git commit -m "Your commit message"

8️⃣ Push changes to the specified branch:
git push -u origin <your-branch>

🚀 You're all set!
