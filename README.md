## Steps for Creating Repository > Git > GitHub
1. Navigate to document directory
    cd ~/Document
Optional: List content of current directory
    ls
2. Create a folder named GitIntro
    mkdir GitIntro
3. Navigate to newly created GitIntro folder
    cd GitIntro (notice you do not need ~/ because you are not navigating to new directory)
4. Create new empty README.md (markdown) file in GitIntro folder
    Markdown - text to html conversion tool
    touch README.md
5. Open and add text to README.md file
    open  README.md
*Shortkey: Command + S to save file
6a. Remove a file
	rm file
6b. Remove a folder
	rm -rf folder
7. Save file and commit / add a note
	git commit -m “add a note”
	*When you return, you will get a untracked red README.md file
8.  Add all modified and new (untracked) files in the current directory and all subdirectories to the staging area
	git add .    or (git add “specific file”)
	* Now the README.md file should be green

Creating New Repository on GitHub
1. + symbol next to profile on upper right “New Repository”
2. Add name and description
3. Click Create Repository
*This will bring you to a new page with Quick Setup
4. Copy: git remote add origin <repo url>

9. Configure the remote repository in terminal
	Paste: git remote add origin <repo url>

10. Upload local repository content (from terminal) to a remote repository (GitHub)
	git push --set-upstream origin master (done on initial setup)	

