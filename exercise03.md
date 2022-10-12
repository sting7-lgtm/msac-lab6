# Exercise 3 - Configuring your first repository

1. Enable color

        git config --global color.ui auto

2. Set your name

        git config --global user.name "John Doe"

3. Set your email address

        git config --global user.email "john.doe@somewebsite.com"

4. Why did we use the `--global` flag?  (What does that do?)

"It sets the color, username, and e-mail address to apply to my entire system from here on out rather than just the repository I am working in now."


5. Check your git config to show the changes you have made

        git config -l

For more information, check out [Customizing Git Configuration](https://www.git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)