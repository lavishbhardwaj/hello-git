# Hello Git Instructions

---

## Initialize the Project as a Repository

1. Open a command prompt (Windows) or terminal (Mac)
2. Navigate to the project folder
3. Initialize the project as a repository with the `git init` command

## Make your edits to index.html

Open up index.html in the text editor of your choice. Following the comments in the HTML document, make any necessary edits (ex. meta tag, your name, your favourite food, etc.).

After saving your changes, make sure that you are tracking them. 

From the command line, you can add untracked files with the following command: 

`git add <filename>`

Alternatively, to track every file in your directory, use: 

`git add -A`

To make sure that everything was added correctly, you can follow up with:

`git status`

---

## Commit your changes

Next, commit your changes with the following command:

`git commit -m "<Your Message Here>"`

When writing your message, remember to use best practices. You should always write in the present tense (ex. 'this fixes a bug', not 'this fixed a bug') and your message should be descriptive, but your message should not be overly long.

When you have made your commit, you will be ready to submit your project. 

---

## Create GitHub Account and Repository

1. Go to [GitHub](https://github.com/)
2. Create an account username and password that you can remember
3. Once your account has been confirmed, create a repository on GitHub:
    1. Name **hello-git**
	2. Add a description, such as My hello-git repo
	3. Make it **public**
	4. Skip adding a README
	5. Skip adding a license
	6. Skip adding .gitignore
	7. Press the **Create repository** button
4. Copy the **HTTPS** URL as you will need this in the next section.
5. You can optionally follow the instructions shown once your repository, or follow the remaining instructions in this **README**.

## Submitting your work

1. First, make sure the working tree is clean with `git status`.

2. Next, use the following command:

`git branch -m main`

3. Use the URL copied from the previous section and add a remote site to push your local repository to. Now execute each of the following commands (separately):

`git remote add origin https://github.com/yourGitAccount/hello-git.git`

`git push -u origin main`

4. If this is your first time submitting anything from your machine, you will need to sign into your GitHub account. 

	**Note**: When typing your password you will not see any visual feedback (i.e., no bullet operators or asterisks). This is normal.

5. Congratulations! You are all set. 

