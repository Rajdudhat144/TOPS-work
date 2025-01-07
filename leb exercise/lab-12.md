Create a Github repository and document how to commit and push code changes.


            Steps to Create a GitHub Repository and Commit & Push Code Changes

            Create Repository:
            Go to GitHub, click + → New Repository.
            Name it (e.g., my-new-repo), and click Create repository.

            Clone Repository:
            bash
            git clone https://github.com/yourusername/my-new-repo.git
            cd my-new-repo

            Make Changes:
            Create or edit a file (e.g., hello.py):
            bash
            echo 'print("Hello, GitHub!")' > hello.py

            Commit Changes:
            bash
            git add hello.py
            git commit -m "Add hello.py with greeting"

            Push Changes:
            bash
            git push origin main
            Verify on GitHub: Check your repository on GitHub to see the changes.