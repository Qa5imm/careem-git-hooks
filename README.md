### Overview
A git-hook which extracts Jira ticket number from the branch name and add to it commit messages (as per the company convention). Benefit: You no longer have to add ticket number to commit messages.

__Note__: Your branch-name should be as per company convention else it will issue you a warning and won't be able to modify messages.

### Installation
Setting up the hook is quick and easy. Run the following command:

`curl -fsSL https://raw.githubusercontent.com/Qa5imm/git-hooks/main/setup | bash`

It will configure everything for you and will be in effect right away.



### Backdrop

Careem has recently introduced a conventtion of adding Jira ticket numbers into branch names and commit messages. This enables Jira to track key development metrics for each ticket, such as the number of branches created, commits made, and builds executed etc. Recognizing that manually adding these ticket numbers to each commit message will be a hustle for developers (and me esp.). I have implemented a git-hook that extracts the ticket number from the branch name and add it to commit messages. As a result, developers no longer need to manually include the ticket number in their messages, streamlining the workflow and reducing repetitive tasks.
If you want to learn more about how git-hooks work, please read the [blog](https://www.atlassian.com/git/tutorials/git-hooks).



### Contributions
If you believe that something is missing or have suggestions for enhancements, please contribute/let me know. I will try to keep it up-to-date with any changes in conventions or developer needs.

