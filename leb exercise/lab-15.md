Follow a GIT tutorial to practice cloning, branching, and merging repositories.

            Git Tutorial: Cloning, Branching, and Merging
            Clone a Repository:

            Run:
            bash
            git clone https://github.com/yourusername/repository-name.git
            cd repository-name
            Create a Branch:

            Create and switch to a new branch:
            bash
            git checkout -b my-feature
            Make changes, stage, and commit:
            bash
            git add .
            git commit -m "Added feature"
            Merge Branches:

            Switch to main branch:
            bash
            git checkout main
            Pull latest changes:
            bash
            git pull origin main
            Merge the feature branch:
            bash
            git merge my-feature
            Push Changes:

            bash
            git push origin main
            Delete a Branch (optional):

            Delete locally:
            bash
            git branch -d my-feature
            Delete remotely:
            bash
            git push origin --delete my-feature