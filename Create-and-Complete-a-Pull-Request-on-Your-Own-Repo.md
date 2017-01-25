For this example we will make a pull request that brings the changes you've made on the master branch _from_ that branch _to_ the gh-pages branch. To begin, change the displayed branch to the gh-pages one. See the last image in the previous section if you are having trouble finding the location of the dropdown list for your repo's branches.

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/pull-request-btn.png)

Create a new Pull Request by clicking the Pull Request button.

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/compare-repos.png)

The window that opens will look something like this one, with four dropdown menus: "base fork," "base," "head fork," and "compare." In this configuration, the system thinks you're asking to merge changes from one fork (yours) into another (in this case, the original). For this specific Pull Request, we are looking to make changes within our own forked repo, so it is important to change whichever fork (either the "base fork" or "head fork") from the original repo on the msu-anthropology account to one's own account.

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/change-base-fork.png)

Your own account should be the second entry on the list, under msu-anthropology.

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/compare-branches.png)

After choosing your own account on this list, the "base fork" and "head fork" options will disappear and all that will remain are "base" and "compare," where they are set to the same branch: gh-pages.

Remember: "base" is the branch where your changes are going _into_ and "compare" is where the changes are _coming from_. So, for this specific tutorial, you should leave the "base" as "gh-pages" and change the "compare" to "master."

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/create-pull-request.png)

After making this selection, the browser window should hopefully update again, to give you the ability to name the Pull Request (although, it will probably have a name based on the commit you did before), write extra details, and then create it.

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/complete-pull-request.png)

If you have properly made sure you've only made changes to the one branch, the next window will indicate that your Pull Request can be merged automatically. Click "Merge pull request," and then "Confirm merge." After this, your Pull Request is complete and the changes you made should be on the other branch as well.

![](https://github.com/msu-anthropology/daea-fs16/blob/master/wiki/conflicts.png)

However, if you have made changes to both branches, you may see a screen after creating the Pull Request that looks like this, where it says the changes cannot be merged automatically. In this case, please contact me or someone else in LEADR and we will help you resolve the issue.

That's it! If things have gone smoothly, you will have successfully made changes to a file on your own computer, and then sent those changes all the way from that location on your computer to your forked repo on GitHub and into another branch.