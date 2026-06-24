# Progress Log

## 2026-06-07

### Repository Created

Started Meta Backend - Version Control repository.

### Goals

- Learn Git fundamentals
- Understand branching and merging
- Practice version control workflows
- Learn GitHub collaboration techniques
- Build professional development habits

### Status

Ready to begin the Version Control course.

## 2026-06-09

### Completed
- Started Meta Version Control
- Course introduction
- Software collaboration concepts
- Cross-platform teamwork
- Collaboration dialogue exercise
- Introduction to merge conflicts
- Introduction to version control concepts

### Key Takeaways
- Modern software development is collaborative.
- Version control helps teams track and manage changes.
- Merge conflicts can occur when multiple developers modify the same code.
- Collaboration tools are essential for professional development teams.

### Next Session
- Continue Module 1
- Begin core Version Control concepts
- Learn Git fundamentals

## 2026-06-12

### Completed
- What is version control?
- Case study: how Meta engineers collaborate
- Git terminology
- Systems of version control and tools
- History of version control
- Version control in professional software development
- History of revisions
- Staging vs. Production

### Key Takeaways
- Version control tracks changes over time.
- Git is a distributed version control system.
- Professional software development relies heavily on collaboration.
- Staging is used for testing and validation before production deployment.
- Revision history allows teams to track and recover changes.

### Connections to My Workflow
- Working Directory → Staging Area → Commit → GitHub
- Similar to how I currently use:
  - git add
  - git commit
  - git push
- Beginning to understand how Git supports team collaboration and feature development.

### Next Session
- Continue Module 1
- Learn more about Git workflows
- Explore branching and merging concepts

## 2026-06-13

### Completed

- History of version control
- Software collaboration concepts
- Revision history
- Staging vs production
- Knowledge check
- Module quiz

### Key Takeaways

- Version control tracks changes over time.
- Git allows developers to safely manage project history.
- Staging acts as a preparation area before committing changes.
- Professional teams collaborate through shared repositories.

### Next

- Module 2: Command Line
- Learn directory navigation
- Learn basic terminal commands
- Connect command line usage to Git workflows


## 2026-06-14

### Completed

- Using Bash on Windows
- Introduction to Command Line: Checking the Working Directory
- Change directories and list contents
- Creating and moving directories and files
- Creating and navigating directories and files

### Key Takeaways

- pwd displays the current working directory.
- ls displays files and folders in the current directory.
- cd changes directories.
- Directories can be created and organized through the command line.
- Navigation skills are foundational for Git and backend workflows.

### Next

- Create and Manipulate Directories and Files (Lab)
- Self Review
- Pipes

## 2026-06-16

### Completed

- Create and Manipulate Directories and Files (Lab)
- Self Review: Make and change directories and files

### Key Takeaways

- Practiced creating directories and files from the command line.
- Practiced navigating directory structures using terminal commands.
- Reinforced usage of cd, ls, pwd, and mkdir.
- Learned that command-line tasks require careful attention to directory location and command syntax.
- Successfully completed the self-review after working through mistakes and troubleshooting.

### Reflection

The self-review was more challenging than expected, but it helped reinforce the command-line concepts from the module. Working through mistakes improved my understanding of filesystem navigation and command usage.

### Next

- Pipes
- Additional command-line concepts
- Continue Module 2

## 2026-06-18

### Completed

- Pipes
- Redirection

### Key Takeaways

- Pipes allow the output of one command to become the input of another command.
- Redirection allows command output to be written to files instead of the terminal.
- Commands can be combined to create more efficient workflows.
- Pipes and redirection are foundational concepts in Unix and Linux environments.

### Backend Connection

- Pipes help process command output efficiently.
- Redirection is commonly used for logs, reports, and automation.
- These concepts are widely used on Linux servers and in backend workflows.

### Next

- Continue Module 2
- Additional command-line concepts
- Further terminal practice

## 2026-06-19

### Completed

- Grep
- Exploring Shell Commands for File and Text Processing (Lab)
- Unix Commands Knowledge Check
- Module Quiz: Command Line
- Module Summary: Command Line

### Key Takeaways

- grep is used to search for text inside files.
- Shell commands can be combined to process files and text efficiently.
- Command-line tools are powerful when used together.
- Linux and Unix commands are foundational for Git and backend development.

### Backend Connection

- grep is commonly used for log analysis and troubleshooting.
- Text-processing tools help developers find information quickly.
- Command-line skills support backend workflows, automation, and server management.

### Next

- Module 3: Working with Git
- Git fundamentals
- Repository workflows

## 2026-06-20

### Completed

- How Git Works
- Add and Commit
- Branches
- Remote vs Local
- Push and Pull
- Repository Lab
- Created working_with_git.md notes
- Created repository_lab/result.txt artifact

### Key Takeaways

- Git tracks project history through commits.
- Branches allow developers to work independently without affecting the main branch.
- Local repositories exist on a developer's machine, while remote repositories enable collaboration and backup.
- Push and pull synchronize local and remote repositories.
- Repository workflows follow a consistent process: status → add → commit → push.

### Backend Connection

- Version control is essential for professional software development.
- Git enables safe experimentation, collaboration, and recovery of previous work.
- Repository workflows are used throughout backend, frontend, DevOps, and infrastructure projects.

### Reflection

This module reinforced concepts I have already been using in my personal repositories. Understanding the terminology behind branches, local vs remote repositories, and repository workflows helped connect my practical Git experience to professional development practices. Creating the repository lab artifact provided additional practice with the complete Git workflow.

### Artifacts

- notes/working_with_git.md
- exercises/repository_lab/result.txt

### Next

- Resolving Conflicts
- Self Review
- Continue Module 3
- Additional Git practice

## 2026-06-21

### Completed

* Merge lab (local repository version)
* Created and switched branches
* Created branch-specific commits
* Merged a feature branch into main
* Learned how HEAD tracks the current branch/commit
* Created merge-lab artifact
* Pushed changes to GitHub

### Key Takeaways

* Branches allow isolated development without affecting main.
* HEAD points to the currently checked-out branch or commit.
* Commits made on a branch remain isolated until merged.
* Merging incorporates branch changes into main.
* Git log can be used to verify commit history and repository state.

### Reflection

Today was the first time I intentionally worked through a complete branching and merging workflow in my own repository. Using my actual Meta Backend repository instead of a temporary lab helped reinforce how Git is used in real projects. I am beginning to think about Git as a workflow rather than a collection of commands.

### 2026-06-22

#### Completed
- Diff Commands

#### Key Takeaways
- git diff compares changes between files, commits, or branches.
- Diff output helps identify what was added, modified, or removed.
- Diff is useful before committing changes to verify work.

#### Next
- Blame
- Forking
- Knowledge Check

### 2026-06-23

#### Completed
- HEAD
- Forking

#### Key Takeaways
- HEAD points to the currently checked-out branch or commit.
- Forking creates an independent copy of a repository.
- Forks are commonly used in open-source development to contribute changes without direct access to the original repository.
- Contributors typically create branches in their fork and submit Pull Requests back to the original project.

#### Reflection
While I could not meaningfully fork my own repository within the same GitHub account, I understood the workflow and how it differs from local branching. The merge-lab artifact I created earlier demonstrated many of the same concepts used in collaborative development.

#### Next
- Knowledge Check: Git and GitHub
- Additional Resources 

### 2026-06-24

#### Completed
- Knowledge Check: Git and GitHub

#### Result
- Score: 83.33%
- Passed on first attempt

#### Key Takeaways
- Local repositories exist on the developer's machine.
- Remote repositories exist on servers such as GitHub.
- Cloning creates a local copy of a remote repository.
- Git workflows involve local development and synchronization with remotes.

#### Next
- Additional Resources
- Continue Meta Version Control course