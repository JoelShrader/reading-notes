# Revisions and the Cloud
An alternative to making changes directly on GitHub is copying or 'cloning' a repository onto my computer, then using the Terminal and VS Code to make the wanted changes.

## Editing code locally
1. On GitHub, select the wanted repository and click the green 'Code' button. Then click on 'Clone'.
2. Open the Terminal, then navigate to the directory you want to clone the repository to, such as `cd Desktop`
3. Copy the .git link in the Code dropdown menu, then put `git clone` followed by the copied link. This will make a copy of the repository in the location you specified earlier
4. Use `cd` followed by the name of your new directory to navigate into it, then use `code .` to open VS Code referencing the files.
5. Edit and otherwise change files through VS Code
6. When satisfied, the following steps in the Terminal will add your changes to the GitHub version of the repository:
    - `git status` shows the changes
    - `git add .` creates a 'stage' to be used by git to add all changes
    - `git commit -m 'short message'` where 'short message' is why you did what you did to add this to the repository version record
    - `git push origin main` to add or 'push' the changes to your GitHub repository

# Site Navigation 
- [Home](README.md)
- [Growth Mindset](Growth_Mindset.md)
- [Learning Markdown](Learning_Markdown.md)
- [Coder's Computer](Coders_Computer.md)
- [Revisions and the Cloud](Revisions_and_the_Cloud.md)
- [Structure Web Pages with HTML](Structure_Web_Pages_with_HTML.md)
- [Design Web Pages with CSS](Design_Web_Pages_with_CSS.md)
- [Dynamic Web Pages with JavaScript](Dynamic_Web_Pages_with_JavaScript.md)