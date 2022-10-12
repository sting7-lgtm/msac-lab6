# Exercise 9 - Viewing history

1. Make a commit with a multi line commit message
   (leaving an empty line after the first line)

2. View that commit in the log

        git log -1

3. View the full commit log

        git log

*If the log fills your whole terminal, press `q` to exit*

4. View a shortened version of the commit log

        git log --oneline

5. Pick a commit hash from the log

6. View the commit log from the chosen commit backward

        git log --oneline <commit_hash>

7. How much of the commit hash do you need to specify? Hint, run `git help log`
"Four characters seems to be enough if there is no overlap between multiple commits"

8. How can you show just the last three commit messages?

"I can type git log --oneline -n 3  

The number at the end is how many commit messages I want to display, starting from the newest"
