# About this repository
This repository was created for practicing what I learned from a Bedu training on Web Development with JavaScript.

<!-- This is my first commit -->
## What is GitHub markdown?
The Markdown API enables you to render a markdown document as an HTML page or as raw text.

You can read more about GitHub markdown in the following link:
- Markdown: https://docs.github.com/en/rest/markdown

As the programming language is not important right now, I am only practicing GitHub markdown. You can read how to get started with markdown in the following page: [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

GitHub markdown is useful for documenting projects that live in GitHub. Documentation is really important when working collaboratively, as an advice, you can include a brief description of your project and also the steps that need to be followed for setting up your project in case more developers collaborate with you.

<!-- This is my second commit -->
## GitHub basic commands
Now, I will describe the most common git commands that we usually use as developers on daily basis. It is important to mention that all these commands were reviewed during the first phase of our Bedu training.

| Command | Description |
| --- | --- |
| git config --global user.name "[firstName lastName]" | Set a name that is identifiable for credit when review version history |
| git config --global user.email "[email]" | Set an email address that will be associated with each history marker | 
| git init | Initialize an existing directory as a Git repository |
| git status | List all new or modified files |
| git add [file] | Add a file as it looks now to your next commit |
| git commit -m "[descriptive message]"| Commit your staged content as a new commit snapshot |
| git branch | List your branches. An * will appear next to the currently active branch |
| git branch [branch-name] | Create a new branch at the current commit |
| git checkout | Switch to another branch and check it out into your working directory |
| git merge | Merge the specified branch's history into the current one |
| git remote add [alias] [url] | Add a git URL as an alias |
| git push [alias] [branch] | Transmit local branch commits to the remote repository branch |

If you want to learn more useful git commands, take a look at the following link which is the GitHub Git Cheat Sheet: [GitHub Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

I really recommend you to download and print the GitHub Cheat Sheet and have it handy so that you can learn all the git commands easily.

<!-- This is my third commit -->
## Notes about the first phase of our Bedu training
In this section, I will document some of the most important aspects that we reviewed during our the first phase of our Bedu training.

### What is git?
 Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency

 - Download git from https://git-scm.com/downloads

 ### What is GitHub?
GitHub is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management (SCM) functionality of Git, plus its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project.

### Difference between Git and GitHub
The key difference between Git and GitHub is that Git is an open-source tool developers install locally to manage source code, while GitHub is an online service to which developers who use Git can connect and upload or download resources.

### What is Git flow?
Giflow is an alternative Git branching model that involves the use of feature branches and multiple primary branches. It was first published and made popular by Vincent Driessen at nvie. Compared to trunk-based development, Giflow has numerous, longer-lived branches and larger commits. Under this model, developers create a feature branch and delay merging it to the main trunk branch until the feature is complete. These long-lived feature branches require more collaboration to merge and have a higher risk of deviating from the trunk branch. They can also introduce conflicting updates.

- More information here: https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow

### What is CVS?
CVS is a version control system, an important component of Source Configuration Management (SCM). Using it, you can record the history of sources files, and documents.

 CVS is (old) centralized version control system, while Git is distributed.

 ### What is Apache Subversion (SVN)?
 Apache Subversion is a software versioning and revision control system distributed as open source under the Apache License. Software developers use Subversion to maintain current and historical versions of files such as source code, web pages, and documentation.

 ### What is Mercurial?
 Mercurial is a free, distributed source control management tool. It efficiently handles projects of any size and offers an easy and intuitive interface.

 The biggest difference between Mercurial vs. Git is the branching structure. It can be argued that branching is better in Git than in Mercurial. Even though Mercurial may be easier to learn and use, its branching model often creates confusion.

 ### What is Monotone?
 Monotone is an open source software tool for distributed revision control. Monotone tracks revisions to files, groups sets of revisions into changesets, and tracks history across renames. The focus of the project is on integrity over performance.

 