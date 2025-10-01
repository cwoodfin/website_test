# Step 1

That's a smart move! Using index.html is the standard practice, as web servers automatically look for that filename when someone visits the base domain.

First, I'll rename and update the file for you.

1. File Renamed to index.html
I've updated the file path to index.html so it's ready for deployment.
Full-Screen Video Background
Oct 1, 4:57 PM

2. Guide to Using Git and GitHub
This guide assumes you have Git installed on your computer. If not, you can download it from git-scm.com and follow the install instructions.

Step 1: Initialize Your Project Folder
Create a Folder: Create a new folder on your desktop (e.g., video-website).

Save the File: Copy the content of the index.html file above and save it inside this new folder as index.html.

Open Terminal/Command Prompt: Navigate into that folder using your command line:

Bash

cd Desktop/video-website
4.  **Initialize Git:** Turn this folder into a Git repository:
```bash
git init

Step 2: Set Up the GitHub Repository
Create on GitHub: Go to GitHub.com and create a New Repository.

Give it a name (e.g., video-landing-page).

Make sure it is set to Public if you plan to use GitHub Pages for free hosting.

Do not check the box to add a README or license yet.

Copy Remote URL: After creation, GitHub will give you a quick setup guide. Copy the line that starts with git remote add origin....

Step 3: Add and Commit Your Code
Now, back in your terminal, run these commands:

Stage Files: Tell Git to track the index.html file:

Bash

git add .
2.  **Commit Changes:** Save the current state of the file with a descriptive message:
```bash
git commit -m "Initial commit: full-screen video background page"

Step 4: Link and Push to GitHub
Link Remote: Link your local repository to the GitHub one (use the URL you copied in Step 2):

Bash

git remote add origin https://github.com/YOUR_USERNAME/video-landing-page.git
    *(Replace the URL with the actual one from your GitHub repo.)*
Set Branch (Optional, but recommended):

Bash

git branch -M main
3.  **Push Code:** Send the committed changes up to GitHub:
```bash
git push -u origin main

Step 5: Launch with GitHub Pages
Go to Settings: Back on GitHub, navigate to your new repository. Click on the Settings tab.

Find Pages: In the left sidebar, click on Pages.

Set Source: Under "Build and deployment," ensure the "Source" is set to Deploy from a branch.

Under "Branch," select main and `/ (root)** for the folder.

Save: Click Save.

GitHub will now deploy your site. It usually takes less than a minute. The page will refresh and show you the live URL (e.g., https://YOUR_USERNAME.github.io/video-landing-page/).

If you make any future edits to index.html, all you need to do is repeat Step 3 (git add ., git commit -m "Your update message", and git push). GitHub Pages will automatically update your live website!
