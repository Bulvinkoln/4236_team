Create Git branch using checkout

The easiest way to create a Git branch is to use the “git checkout” command with the “-b” option for a new branch. Next, you just have to specify the name for the branch you want to create.

$ git checkout -b <branch-name>

As an example, let’s say that you want to create a new Git branch from the master branch named “feature”

To achieve that, you will run the “git checkout” command with the “-b” option and add “feature” as the branch name.

$ git checkout -b feature
Switched to new branch 'feature'

As you can see, by using the “git checkout” command, you are creating a new branch and you are switching to this new branch automatically.