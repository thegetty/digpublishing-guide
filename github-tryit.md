## GitHub: Try It

### Creating a local copy of the repository

Our main project repository (made up of all the associated files for the project) is being hosted on GitHub, a project management site that uses Git for version tracking. While you can make changes directly to the repository files through the web interface at [https://github.com/gettypubs](https://github.com/gettypubs), for the most part you will instead want to work on your own local copies of the files.

> Using GITHUB DESKTOP: Go to File > Clone Repository (ˆ⌘O), select the repository from the list, and select where on your computer you'd like to keep it.

### Working in your local copy

GitHub connects your local copy of the repository to the main copy hosted on GitHub.com. If you make any change on your local files (including fixing a single typo, or adding or deleting entire files and folders within the repository) and then you commit and synch those changes through GitHub Desktop, they will be copied to the main repository. All changes (commits) are recorded and tracked, and can be reverted at anytime.

If changes are made and saved on the files but not committed, as far as GitHub is concerned, they never happened. Typically, you'll be updating the project in three steps: Save, commit, synch.

1. SAVE changes to the file
2. COMMIT those changes to the Git record
3. SYNCH the new commits in your local copy to the copy hosted on GitHub, as well pushing any new commits in the GitHub copy, back down to your local one.

While saving happens in whatever program you're working on the files in, committing and synching happen in GitHub Desktop, often simultaneously, and often involving multiple recently saved files.

### Making related and well-described commits

Every time you make a commit to the repository, GitHub also asks you to add a brief summary statement as well as a description explaining the changes made. These *commit messages* are important. By writing clear commit messages, you make it easier for other people working on the project to follow along and provide feedback. A commit for a typical book project might be:

> SUMMARY: Copyedits to Chapter 2  
DESCRIPTION: Input all compiled Chapter 2 copyedits from copyeditor and author on second round of proofs. One outstanding query remains on name of artist's dog.

Each commit you make is a separate unit of change. While some commits will be small changes to single files, for bigger changes it is best to compartmentalize your work around related areas or tasks, and then to commit the changes in that area all at once before moving on to the next item. This helps you write clear commit messages, but also keeps related changes bundled together making them easier to track, and potentially undo, down the road. Some good commits would be:

- All copyedits to a single chapter
- Resizing all images in the publication to a standard size
- Renumbering all footnotes
- Making all changes necessary to fix a single bug
- Fixing all occurrences of a misspelled name throughout a book

### Working in branches

Before changing or committing anything, you’re usually going to want to create a new branch of the repository. A branch is an environment where you can work without affecting the master, so you’re free to experiment and make multiple commits, safe in the knowledge that your branch won’t be merged back into the master until it’s fully reviewed and tested.

Branches are another way of grouping together similar work in the repository. Always create branches from the master, and name them descriptively:

- second-round-edits
- final-proofread
- alternative-page-order-and-intro

Creating a branch is different than cloning the repository. Cloning the repository creates a second set of files that are synched together so that a change in one set is copied to the other. Branching a repository only creates an alternate version of the same files, where a change is one version has no effect on the other.

A branch lives side by side other branches in the repository. Or rather, they live on top of one another. When you look at your local copy of the repository, you will only ever see one set of files, no matter how many branches there are. GitHub Desktop and GitHub.com both tell you what branch you’re in currently, and what other branches are included in the repository. When you switch branches, GitHub switches your view of the files, showing you only the files and versions of files that are part of that branch. When working in your local copy, and when making commits, you’ll always want to double check you’re in the branch you want to be in.
