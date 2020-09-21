
:::::::::::::::::::::::::::{ .firstslide}
# Current History controls

![](src/Images/galaxy_logos_all.png)


::::::::::::::::::::::::::::::::::::::::::





# The Current History

:::::::{ .spoken .document}
When data is uploaded from your computer or an analysis is done on existing data using Galaxy, each output from those steps generates a dataset. These datasets, and the output datasets from later analysis on them, are stored by Galaxy in Histories.

All users have one <i>current</i> history, which can be thought of as a <b>workspace </b> or a <b>current working directory</b> in bioinformatics terms. Your current history is displayed in the right hand side of the main <i>Analyze Data</i> Galaxy page in what is called the history panel.
The history panel displays output datasets in the order in which they were created, with the oldest/first shown at the bottom. As new analyses are done and new output datasets are generated, the newest datasets are added to the top of the the history panel. In this way, the history panel displays the history of your <b>analysis over time</b>

<b>Users that have registered an account and logged in can have many histories</b> and the history panel allows switching between them and creating new ones. This can be useful to organize different analyses.

<b>Anonymous users</b> (if your Galaxy allows them) are users that have not registered an account. Anonymous users are only allowed one history. On our main, public Galaxy server, users are encouraged to register and log in with the benefit that they can work on many histories and switch between them.

The histories of anonymous users are only associated through your browser's session. So if you close the browser or clear you sessions - <b>that history will be lost!</b> We can not recover it for you if it is.
::::::::::::::::::::::::::::::


::::{ .wide}
![Galaxy History is simply the right panel of the interface.](src/Images/history.png "Galaxy History is simply the right panel of the interface")
::::::::::::::::::::::::::::::::


:::{ .warning .onslides}
<b>Important !</b> <b>If you close the browser or clear you sessions - that history will be lost! </b> We can not recover it for you if it is.
::::::::::


# Current history controls

::::{ .small}
![History Controls.](src/Images/current-history-buttons.png "History Controls")
::::::::::::::::

::::{ .spoken .document}
Above the current history panel are three buttons: the <i>refresh</i>, <i>New history</i>, <i>history options</i>, and <i>view all histories</i> button.
The <i>refresh</i> button will entirely reload the history being viewed. This can be helpful if you believe the history interface needs to be updated or isn't updating properly.
The <i>New history</i> button will create a new empty history and make it your current history.
The <i>history options</i> button opens the history options menu which allows you to perform history-related tasks.
The <i>view all histories</i> button sends you to the interface for managing multiple histories.
::::::::

::::{ .onslides}
**Refresh** : Reload the history being viewed

**New History** : Create a new current history

**History options** : Opens the history options menu

**View all histories** : Sends you to the interface for managing multiple histories
::::::::


# History Information

### Renaming a history

:::::::::{ .spoken .document}

Histories also store information in addition to the datasets they contain. They can be named/re-named, tagged, and annotated.

All histories begin with the name <i>Unnamed history</i>. Non-anonymous users can rename the history as they see fit.

First, Click the existing name. A text input field will appear with the current name. Enter then a new name or edit the existing one. Finally, Press <kbd>Enter</kbd> to save the new name. The input field will disappear and the new history name will display. To cancel renaming, press <kbd>Escape</kbd> or click outside the input field.
::::::::::::::::::


::::{ .wide}
![Renaming a history by clicking on its name and entering a new one](src/Images/renaming.png "Renaming a history by clicking on its name and entering a new one")
::::::::::::::::::::

::::{ .onslides}
1. Click existing name.
2. Enter a new name
3. Press <kbd>Enter</kbd> to save
4. Press <kbd>Esc</kbd> To cancel
::::::::::::

# [History Information]{ .onslides}

### Tagging a history

:::::::::{ .spoken .document}
Tags are short pieces of text used to describe the thing they're attached to and many things in Galaxy can be tagged.
Each item can have many tags and you can add new tags or remove them at any time. Tags can be another useful way to organize and search your data. For instance, you might tag a history with the type of analysis you did in it: <i>assembly</i> or <i>variants</i>. Or you may tag them according to data sources or some other metadata: <i>long-term-care-facility</i> or <i>yellowstone park : 2014</i>.

Note that it is recommended to replace spaces in tags with underscores or hyphens. Although spaces are allowed in tags for histories, they are removed from the tags for datasets. To tag a history, click the tag button at the top of the history panel. An input field showing existing tags (if any) or a 'plus' icon will appear. Begin typing your new tag in the field. Any tags that you have used previously will show below your partial entry, allowing you to use this 'autocomplete' data to re-use your previous tags without typing them in full. When you are done, press enter or select one of the previous tags with your arrow keys or mouse. To remove an existing tag, click the small <i>X</i> on the tag or use the backspace key while in the input field.
::::::::::::

::::{ .wide}
![Tagging a history will help searching for it later on.](src/Images/tags.png "Tagging a history will help searching for it later on.")
::::::::::::::::::::

1. Click the tag button at the top of the history panel.
2. Type your new tag.
3. Press enter.
4. To remove an existing tag, click the small 'X' on the tag.

# [History Information]{ .onslides}

### Annotating a history

:::::::::{ .spoken .document}
Sometimes tags and names are not enough to describe the work done within a history. Galaxy allows you to create history annotations: longer text entries that allow for more formatting options. The formatting of the text is preserved. Later, if you publish or share the history, the annotation will be displayed automatically, allowing you to share additional notes about the analysis.
To annotate a history, click the annotation button at the top of the history panel. A larger text section will appear displaying any existing annotation, or, if there's none, italic text saying you can click on the control to create an annotation. Click the annotation section. A larger input field will appear. Add your annotations. The <kbd>Enter</kbd> key will move the cursor to the next line. Tabs cannot be entered since the 'Tab' button is used to switch between controls on the page. Tabs can be pasted in however. To save the annotation, click the 'Done' button.
:::::::::::::::::

::::{ .wide}
![Annotating a history allows entering more information such as, for example, experimental details related to the analysis.](src/Images/annotations.png "Annotating a history allows entering more information such as, for example, experimental details related to the analysis")
::::::::::::

::::{ .onslides}
1. Click the annotation button at the top of the history panel.
2. Click the annotation section.
3. Add your annotations.
   - <kbd>Enter</kbd> will move the cursor to the next line.
4. Click the 'Done' button.


::::{ .warning}
<b>History size</b> : The total size of all the datasets in a history is displayed underneath the history name.
::::::

::::::::::::::

:::::::::{ .spoken .document}
As datasets are added to a history, Galaxy will store them on the server. The total size of these files, for all the datasets in a history, is displayed underneath the history name. For example, if a history has 200 megabytes of dataset data on Galaxy's file system, '200 MB' will be displayed underneath the history name.

If your Galaxy server uses quotas, the total combined size of all your histories will be compared to your quota. If you're using more than the quota allows, Galaxy will prevent you from running any new jobs until you've deleted some datasets and brought that total below the quota.
:::::::::::::::::
