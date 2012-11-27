Those helpful git commands

```
The Typical Procedure

# See what files you changed
git status

# Add all changes to the staging area (kind of like the waiting room for a camera session)
git add .

# Or, if you want to add specific files
git add filename

# Commit your changes locally (like taking a picture of all your stuff)
git commit -m "my message about what I did"

# Push your changes. If this doesn't work, do git pull.
git push

# Pull changes
git pull

# See the log of past changes
git log

# Deleted stuff still appearing? This removes 'somefile' from git, so it isn't tracked anymore
git rm somefile

# Tagging
# Tagging a commit from the past - just pass part of the hashcode
# The -a means 'annotated' - the only one we'll ever use
git tag -a design ffd918a8087d6 -m "my message about this tag"
git tag -a v0.0 -m "version 0"

# Push your tags, because they don't go to the remote repo by default
git push --tags

# Deleting a tag (run both commands)
git tag -d tagname
git push origin :refs/tags/tagname

# More tagging stuff...
http://git-scm.com/book/en/Git-Basics-Tagging

# If you want to check out a past tag, v0.0, and poke around the code we had:
git checkout v0.0 
# Just 'git checkout master' when you're done to go back to the master branch

# Branching
# This isn't documented anywhere for some reason... but it's a nice way to switch between 2 branches quickly
git checkout -

*Bonus tricks on github / git
When you're looking at a repo, hit "t". It brings up a nice search field for finding any file. Then you can look at the history of the file and find what you want!
```