**Initialze a reopsitory**

`ls`

`git init`

`ls`

`ls -la`

**Where Git files are Stored**

`ls -la .git`

`cat .git/config`

`git add .`

`git commit -m "Initial commit"`

**Write a commit massage**

A short single-line summary (less than 50 charachters)

Optionally followed by a blank line and a more complete description 

keep each line to less than 72 cahracters

Write commit messages in present tense not past tense

_"Fix for a bug"_ or _"Fixes a bug"_ not _"Fixed a bug"_


**View the commit log**

`git log`

`git help log`

`git help log -n 5`

`git log --since=2019-01-01`

`git log --until=2019-01-01`

`git log --grep="Init"`