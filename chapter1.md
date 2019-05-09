---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
free_preview: true
---

## Insert exercise title here

```yaml
type: TabExercise
key: dffd96819c
xp: 100
```

The intention of this worksheet is to introduce you to some of the commands in the dplyr package in R (which we will continue to look at next week) and further familiarize you with the ggplot2 package.

As always, be sure to save your work as you progress through this file! To do so, use "File -> Save As" in the toolbar above and save it to the folder that you created for DATA100 in Week 1.  

Once saved, go to "Session -> Set Working Directory -> Choose Directory..." in the toolbar at the top of this page and navigate to your DATA100 folder.

Additional Notes:

i) Any of the "white" areas in this file (called an R notebook) are where text can be input into the document.

ii) Any of the "grey" areas are where R code is entered (called "code chunks").  To execute any of the code chunks, push the run button (looks like a "play" button) in the top right of the code chunk. Alternatively, "Ctrl+Shift+Enter" will also run the code chunk.

iii) Code chunks will always start with '''{r} and end with '''.  If necessary, to insert a code chunk you can click on "Insert" along the tool bar and choose R or "Ctrl+Alt+I".  For the most part, code chunks will be given and you won't need to insert them in the file.

**SETUP**

Before we get started, load the tidyverse package which contains the dplyr package.

`@pre_exercise_code`
```{r}
install.packages("tidyverse")
library(tidyverse)
```
