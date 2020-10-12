



:::::::::::::::::::::::::::{ .firstslide}
# Hiding and deleting datasets

![](src/Images/galaxy_logos_all.png)


::::::::::::::::::::::::::::::::::::::::::


#  Hiding and deleting datasets

:::::::::::::::::::::::::::::::::::{ .two_col}

:::::::::::::::::::::::{.col}

### Hiding and unhiding datasets

::::::{ .spoken .document}
Some procedures in Galaxy such as workflows will often <b>hide</b> history datasets in order to simplify the history and hide intermediate steps of an automated analysis. These hidden datasets won't normally appear in the history panel but they are still mentioned in the history subtitle (the smaller, grey text that appears below the history name). If your history has hidden datasets, the number will appear there as a clickable link. If you click this link, the hidden datasets are shown. Each hidden dataset has a link in the top of the summary view that allows you to unhide it. You can click that link again (which will now be <i>hide hidden</i>) to make them not shown again. The Left side of the image shows a history with one hidden dataset. We know this because a link <i>1 hidden</i> appears under the history's name. Clicking this link will reveal the hidden dataset as shown on the right side of the figure.
:::::::::::::

::::{ .square}
![Left: history with one hidden dataset. Right : Dataset with an unhidden hiden dataset.](src/Images/hide.png "Hiding and unhiding datasets. Left side shows a history with one hidden dataset. We know this because a link "1 hidden" appears under the history's name. Clicking this link will reveal the hidden dataset as shown on the right side of the figure.")
::::::::

:::::::::::::::::::::::::

:::::::::::::::::::::::{.col}

### Deleting and undeleting datasets

::::::{ .spoken .document}
You can <b>delete</b> any dataset in your history by clicking the delete button. This does not immediately remove the dataset's data from Galaxy and </b>it is reversible</b> When you delete a dataset from the history, it will be removed from the panel but, like hidden datasets, the total number of deleted datasets is shown in the history subtitle as a link. Clicking this link will make the deleted datasets visible, and each deleted dataset will have a link for manually undeleting it above its title. You can click that link again (which will now be 'hide deleted') to make them not shown again.  The left side of the image shows a history with one deleted dataset. We know this because a link <i>1 deleted</i> appears under the history's name. Clicking this link will reveal the deleted dataset as shown on the right side of the figure. From here it can be undeleted or deleted permanently.
::::::::

::::{ .square}
![Left: history with one deleted dataset.  Right : Dataset with an unhidden deleted dataset.](src/Images/delete.png "Deleting and undeleting datasets. The left side shows a history with one deleted dataset. We know this because a link '1 deleted' appears under the history's name. Clicking this link will reveal the deleted dataset as shown on the right side of the figure. From here it can be undeleted or deleted permanently.")
:::::::::

:::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::::::::::

# Purging datasets and removing them permanently from Galaxy

:::::::::{ .spoken .document}
If you are showing deleted datasets and <i>your Galaxy allows users to purge datasets</i>, you will see an additional link in the top of each deleted dataset titled <b>Permanently remove it from disk</b>. Clicking this will remove the file that contains that dataset's data and will decrease the disk space used by the history. <b>This action is not reversible and cannot be undone</b>.  If your Galaxy doesn't allow users to purge their datasets, you will not see that link.
:::::::::::::::::

- Show deleted dataset
- Click **'Permanently remove it from disk**' on top of the dataset

:::{ .warning}
**This action is not reversible and cannot be undone**
::::::

:::{ .warning}
**Admins may purge your deleted datasets**
::::::

:::::::::{ .spoken .document}
Depending on the policy of your Galaxy server, administrators will often run scripts that search for and purge the datasets you've marked as deleted. Often, deleted datasets and histories are purged based on the age of the deletion (e.g. datasets that have been marked as deleted for 90 days or more). Check with the administrators of your Galaxy instance to find out the policy used.
:::::::::::::::::


:::::::::::::::::::::::::::{ .firstslide}
# Hiding and deleting datasets

![](src/Images/galaxy_logos_all.png)


::::::::::::::::::::::::::::::::::::::::::
