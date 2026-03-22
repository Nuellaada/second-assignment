# second-assignment

## Version Control
Version control is a system that tracks changes made to files over time, allowing you to recall specific versions later. With version control, you can see who made changes, what was changed, and when and you can revert to a previous state if something goes wrong.

## Difference between Git and Github
**Git** is a free, open-source version control tool installed on your local computer. It tracks changes to your files and manages your project history entirely offline.

**GitHub** is a cloud-based platform that hosts Git repositories online. It adds a web interface, collaboration tools, pull requests, and issue tracking on top of Git. In short: Git is the tool, GitHub is the service that stores and shares your Git projects.

## 3 Github Alternatives
1. **GitLab** – A web-based DevOps platform that offers Git repository hosting along with built-in CI/CD pipelines and project management tools.
2. **Bitbucket** – A Git repository hosting service by Atlassian, popular for teams that also use Jira and Confluence.
3. **Azure DevOps (Azure Repos)** – Microsoft's platform for hosting Git repositories, integrated with their suite of developer and cloud tools.

## Git Fetch vs Git Pull
- **git fetch** downloads changes from the remote repository to your local machine but does not apply them to your working files. It lets you review changes before integrating them.
- **git pull** downloads the changes and immediately merges them into your current branch. It is essentially git fetch + git merge combined in one command.

## Git Rebase
Git rebase moves or replays your commits onto a new base commit, creating a cleaner, linear project history. It is saying: "Apply my changes as if I had started from this newer point."
**Command:**
git rebase <branch-name>

## Git Cherry-Pick
Git cherry-pick lets you pick a single specific commit from one branch and apply it to another branch — without merging the whole branch. It is saying: "I only want that one change, not everything else."
**Command:**
git cherry-pick <commit-hash>