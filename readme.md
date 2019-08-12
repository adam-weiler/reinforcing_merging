### Thursday, Aug 8th
# 01 - Reinforcing Exercises: Git Merge

These short exercises will give you a chance to practice the fundamental programming concepts you've learned so far.
## Prerequisites

+ HTML and CSS fundamentals
+ Assignment on Git branching and merging

## Exercise

1. [Fork and clone this repository](https://github.com/bitmakerlabs/reinforcing_merging) containing a simple HTML page and three separate branches that need to be merged.
2. Run `git branch -a` to see all the existing branches. There should be two remote branches in addition to `master`: `* master remotes/origin/HEAD -> origin/master remotes/origin/master remotes/origin/sections remotes/origin/styling`
3. Take a brief look at the changes on both the `styling` and `sections` branches (both in your editor and in your browser to see what the changes should look like).

_ 

    git checkout styling

and

    git checkout sections

1. Go back to the master branch.
2. Pick one of the two other branches and merge it into the master branch.
3. Now merge the other branch into master.
4. Resolve the merge conflicts so that all changes from `styling` and `sections` are combined into a reasonable final project (there are multiple ways of doing this). Check your work in the browser to make sure it looks decent.
5. Don't forget to commit to indicate the merge is complete.

