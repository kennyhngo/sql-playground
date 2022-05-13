# SQL Playground

Used in EECS 484 - Database Management Systems to play around with SQL commands and queries. Not easy as creating a new SQL file and coding, like in Python or C++.

If it creates a new git repoository and you don't want the annoying line changes in VSCode, then delete everything in `.gitignore` and add this to line 1: `*`. That will tell `.gitignore` to ignore everything, and the source control will never pop up and bug you.

OR you can remove the git repository all together with `rm -rf .git`

# Usage
1. Clone the repository.
2. Change only `schema.sql` and `data.sql` to run whatever code you want.
3. Run `./rundb`
