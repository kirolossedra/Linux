Add the Changes: Add the files you want to commit to the staging area. You can add specific files or all changes.

bash
Copy code
git add filename1 filename2
Or to add all changes:

bash
Copy code
git add .
Commit the Changes: Commit the changes with a descriptive message.

bash
Copy code
git commit -m "Your commit message here"
Push the Changes: Push your changes to the remote repository on GitHub. Typically, you’ll push to the main branch (or master if that’s what your repository uses).

bash
Copy code
git push origin main




Force Push to Remote:
Use the --force option (or -f for short) with git push to overwrite the remote branch:

bash
Copy code
git push --force origin main
