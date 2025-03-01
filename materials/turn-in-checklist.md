---
layout: page
title: Assignment Submission & Checklist
---

- All assignments should be submitted through [D2L](https://d2l.coloradomesa.edu/d2l/home/233299)

- What files to submit: 
    - **Week 1** - Show instructor that you have completed assignment
    - **Week 2-3** - an R script
    - **Weeks 4** - one text form, one .xlsx file
    - **Weeks 5-17** - an R script

**NOTE for Fall 2023:** 
  - Week 4 will be remote
  - Week 8 will be remote
  - Week 14 is Fall Break
  - Week 17 is Finals week

## Code Checklist

### Make sure your code matches the provided answers

- At the bottom of each exercise a set of answers are provided. For full credit
  your answers should match those provided. For example, if there are three
  separate plots your code should produce three separate plots.
- Some errors can lead to only subtle differences so check carefully
- Sometimes small differences result from changes in packages. If you see a
  difference but you think your answer is right, let us know and we can check.

### Make sure your code follows the instructions

- It is possible to get the right output even when doing something the wrong way
- To get full credit on assignments you need to both follow the instructions and
  get the right output

### Clean up your code

Code should be easy to read and understand.

- Only include code and comments necessary for the assignment. Remove anything else (e.g., notes taken during class, commented code that isn't needed anymore).
- Remove extra/duplicate files. Only turn in what is necessary for the assignment.
- Remove any uses of `install.packages`
- Clearly label problems using comments.

### Make sure your code runs like you think it does

Code should run from the start of the file to the end of the file without problems. To make sure this is true:

- Restart the R environment by clicking on the `Session` menu item and then `Restart R`.
- Run the entire file by either clicking the `Source` button or using the `Ctrl-Shift-S` keyboard shortcut.

### Work with data files appropriately

Code should run the same way regardless of which computer it is run on. In order to grade your code someone will need to run it on another computer. To make sure your code will work on another computer:

- Do not use setwd()
- Use relative paths, not absolute paths. E.g., use `data/mydata.csv` instead of `C:\Users\Batman\DataCarp\data\mydata.csv`.
- Make filenames in the code match the actual filenames exactly including capitalization
