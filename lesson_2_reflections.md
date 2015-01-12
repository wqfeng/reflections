
## What happens when you initialize a repository? Why do you need to do it?

There is a hidden directory .git created under the current directoy. It contains the meta data to make my files managed by Git.

## How is the staging area different from the working directory? What value do you think it offers?

It's quite a tough question!

## How can you use the staging area to make sure you have one commit per logical change?

I can compare the staging area with the most recent commit with `git diff --staged`.