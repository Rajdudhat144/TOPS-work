Write and upload your first source code file to Github.



            Steps to Write and Upload Your First Source Code File to GitHub:
            Set Up Git:

            bash

            git config --global user.name "Your Name"
            git config --global user.email "your.email@example.com"
            Create a Repository on GitHub:

            Go to GitHub, create a new repository (e.g., my-first-repo), and initialize it with a README.
            Write Source Code:

            Create a file hello.py with a simple program (e.g., print("Hello, World!")).
            Initialize Local Git Repository:

            bash

            git init
            git add hello.py
            git commit -m "Add hello.py"
            Link Local Repo to GitHub:

            bash

            git remote add origin https://github.com/yourusername/my-first-repo.git
            Push to GitHub:

            bash

            git push -u origin master
            Verify:

            Go to your GitHub repo to see the uploaded file.