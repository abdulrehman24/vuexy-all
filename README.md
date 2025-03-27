# Uploading Large Files to GitHub

GitHub has file size limitations, but you can use **Git LFS (Large File Storage)** to manage large files effectively. Follow these steps to upload large files:

## Steps to Upload Large Files

### 1️⃣ Initialize a Git repository:
```sh
git init
```

### 2️⃣ Connect to a remote GitHub repository:
```sh
git remote add origin <github-link>
```

### 3️⃣ Set up user details (if not configured globally):
```sh
git config user.name "<your-name>"
git config user.email "<your-email>"
```

### 4️⃣ Install Git LFS (if not already installed):
```sh
git lfs install
```

### 5️⃣ Specify file types to track with Git LFS:
```sh
git lfs track "*.zip"  # Modify as needed (e.g., "*.mp4", "*.rar")
```
💡 To track all files, use:
```sh
git lfs track "*"
```

### 6️⃣ Stage all files for commit:
```sh
git add .
```

### 7️⃣ Commit changes with a message:
```sh
git commit -m "Your commit message"
```

### 8️⃣ Push changes to the specified branch:
```sh
git push -u origin <your-branch>
```

## 🎉 Congratulations! 
Your large files are now successfully tracked and uploaded to GitHub using **Git LFS**. 🚀
