# Open-saurus Rex
HackPack for VandyHack's workshop about Open Source on July 11th.
Credit to https://github.com/wayou/t-rex-runner for source code.

<img src="https://github.com/wayou/t-rex-runner/raw/gh-pages/assets/screenshot.gif" width="860" align="center"/>

## What is Open Source?
A project is 'open source' if:
* source code is **freely available** to the public
* source code can be **copied, modified, and redistributed** by anyone

## What is Version Control?
A system that records changes made to a project over time and stores previous or multiple states.
Think of a Google Doc as an open source project: every time a change is made to the document, it is immediately saved and recorded in the version history of the document. *This is an example of version control.*

### Why is version control useful?
Version control allows contributors to:
* backup and restore earlier versions of source code
* track changes made to source code over time
* track ownership of changes (who changed what) in collaborative projects
* stay up-to-date on the latest version of a project (especially useful for collaborative projects)
<img src="https://www.linode.com/docs/development/version-control/how-to-install-git-and-clone-a-github-repository/git-github-workflow-1000w.png" width="400" align="right"/>

### Git vs GitHub
* __Git:__ a locally installed version control tool for managing and tracking source code history during software development
* __GitHub:__ a cloud-based hosting service for Git repositories with collaborative features

## The Command Line Interface (CLI)
* `$ git clone https://github.com/link_to_the_repo.git` - download a copy (or clone) an existing repository to your computer
* `$ git add <file-name>` - mark any changes to files in the repository as ready to be committed (or stage changes)
* `$ git pull` - download latest information from the remote/original repository (i.e. new branches) & integrate all new commits made to the remote repository into local repository
* `$ git commit -m “commit message”` - commit and save staged changes locally (in your cloned repository)
* `$ git push` - upload (or push) cloned/local repository to the remote/original repository

## Forking and Pull Requests
* Fork: Get a copy of the repo that you own and can do anything with
* Pull Request: After you make changes of a fork, ask the owner of the main repo to apply them. Also good practice to do this with branches on your own projects!

## Debugging Challenges:
- There are 4 categories of issues to resolve (3 ~ 4 debugging challenges per category):
- [ ] Sound doesn’t play when it should
- [ ] Scoreboard is broken
- [ ] Game doesn’t restart
- [ ] Everything is off-center
