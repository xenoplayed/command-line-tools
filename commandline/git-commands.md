# create a new repository on the command line

    echo "# my-project" >> README.md
    git init
    git add README.md
    git commit -m "initial commit"
    git remote add origin https://github.com/username/my-project.git
    git push -u origin master

# or push an existing repository from the command line

    git remote add origin https://github.com/username/my-project.git
    git push -u origin master