# Basic Version Control Tasks

- ## Explain version control

Version Control is a system that helps a developer to keep track of all the changes that have been made to a source code over time and takes a snapshot of every modification for easy recall of specific versions later. Version Control also makes it possible for a team of developers to collaborate remotely while building a product, tracking all changes and who makes these changes.

- ## Explain difference between git and github

| Git                                                            | Github                                                |
| -------------------------------------------------------------- | ----------------------------------------------------- |
| Git is a software.                                             | GitHub is a service.                                  |
| Git is a version control system to manage source code history. | GitHub is a hosting service for Git repositories.     |
| Git is installed locally on the system                         | GitHub is hosted on the web                           |
| Git is focused on version control and code sharing.            | GitHub is focused on centralized source code hosting. |
| Git is a command-line tool                                     | GitHub is a graphical user interface                  |

- ## List 3 other github alternatives

  1. Bitbucket
  2. Gitea
  3. Azure Repos

- ## Explain the difference between git fetch and git pull

**Git fetch** is a command used to fetch all changes from a remote repository to the local repository. It doesn’t make any changes to the working directory while **Git pull** gets all changes from a remote repository and merges these changes automatically to the working directory.

- ## Explain in simple terms git rebase and the command for it

**Git Rebase**-
Rebasing in Git is a process of integrating a series of commits on top of another base tip. It takes all the commits of a branch and appends them to the commits of a new branch.

![Alt](https://media.licdn.com/dms/image/v2/D4D12AQHQqYpzC7rHBw/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1690994617726?e=2147483647&v=beta&t=dDEjd2QoZVKbiPnktFzpo1NZ14PVcVXMmPEvUikbSkY)

**Git rebase Command:** _git rebase --interactive OTHER-BRANCH-NAME_

- ## Explain in simple terms cherry-pick and the command for it

**Git cherry-pick** command chooses a specific commit from one branch and applies it to another branch. If you commit changes to the wrong branch or want to make the same changes to another branch, you can cherry-pick the commit to apply the changes to another branch It’s great for fixing mistakes and helps maintain a clean and efficient code history.

![Alt](https://media.geeksforgeeks.org/wp-content/uploads/20220302150302/BeforeCherryPick.jpg)
**_before cherry pick_**

![Alt](https://media.geeksforgeeks.org/wp-content/uploads/20220302150549/AfterCherryPick.jpg)
**_after cherry pick_**

**Git cherry-pick Command:** \_git cherry-pick (commit-hash)
