# NOTES

--Add Git Hooks with husky
for learning about husky https://www.youtube.com/watch?v=tuzys2b1J70

what is a git hook ?
Git hooks are feature built in right into git that allows the user to trigger different functionality based on different events of the git process for instance if we want to run a script every time before a commit happens we can use a hook called pre-commit
we can run something like formating and linting (Checks)

-- It's important because having scripts that must succeed before you can push to the repo

-- Scripts (Hooks)

- pre-commiting run yarn lint to check for not errors
- pre-pushing to build runing yarn build
- adding a script called prepare. Prepare is a script that runs when you npm or yarn install. We need this scprit to install the husky hooks for us.

# TODO
