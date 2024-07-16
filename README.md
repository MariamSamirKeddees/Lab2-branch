-   Tell me how to remove them locally and remotely.

To remove them locally:
{git branch -d dev}
{git branch -d test}

To remove them Remotely:
{git push origin :dev}
{git push origin :test}

-   Tell me how to checkout another branch without commit changes.

Use {git stash} to temporarily save changes, then use {git checkout branch_name} to switch to the branch you want to switch to

-   Tell me how to list tags.

Use {git tag} to list tags.

-   Tell me how to delete tag locally and remotely.

Locally => Use {git tag -d v1.7}
Remotely => Use {git push origin --delete v1.7}

![Wallpaper](Impo.PNG)
