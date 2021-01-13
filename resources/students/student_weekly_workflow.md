# Student weekly workflow

## Accepting Assignments
1. Join the new Slack channel for the lab
1. Click on the link to the Github Classroom assignment
1. Accept the assignment invitation
1. Wait for progress bars to complete (should take ~10-20 seconds)
    * It is possible this may hang for a few minutes.  If it is taking longer, post on Slack so we can figure out if it is isolated or others are also experiencing issues.
1. Click on the resulting link to go to your assignment repository (now has your github username appeneded)
1. Enjoy the lab:
    * Read instructions!
    * Write/modify code
    * Git add/commit as you make progress to record "checkpoints" in your work

## Submitting Completed Assignments

### 1. Prepare Jupyter notebook for submission
* Replace `%matplotlib widget` with `%matplotlib inline`
* From the top menu, click Kernel -> Restart Kernel and Run all Cells…
* Your figures are now statically rendered jpg and will be embedded in the notebook for review/grading
    * If you are unhappy with figure size, you can change default figure size by adding `plt.rcParams['figure.figsize'] = [10, 8]` or increasing the dpi, after the  `import matplotlib.pyplot as plt` line, or tweaking each figure size in inches. Note that this will increase the filesize of your notebook!
    * When you’re satisfied, Run All Cells again.  
* Save the notebook by clicking the little floppy disk icon.  

### 2. Git workflow
* In a Jupyterlab terminal, `cd` to your assignment repo
* Use standard git add/commit/push workflow
    * `git add completed_notebook.ipynb`
    * `git commit -m 'Meaningful commit message'`
    * `git push`
* Go to your Github repo, click on the notebook file to render in the browser (might fail the first time if filesize is large, click reload), and verify that everything looks good!

### 3. Canvas submission
* Go to the Canvas assignment page, and submit the url to the Feedback Pull Request on your Github repo
   * Click the Pull Request tab near the top of the page
   * Click the Pull Request named Feedback
   * Copy and paste the url:
      * This should be something like https://github.com/UW-GDA/01_shell_github-dshean/pull/1

### 4. Instructor/TA will review
1. Instructor/TA will review the changes you made (summarized in the Pull Request) and add inline comments/discussion.
1. If your submission is a Jupyter notebook, cell-level comments will be added using ReviewNB
1. Final grade assigned via Canvas
1. Instructor/TA will post solutions to https://github.com/UW-GDA/gda_course_2021_solutions
   * These are meant to be used as a "read-only" reference for you to review after turning in your assignment
   * They represent one set of solutions, and they are not necessarily the most elegant, efficient or best solutions. 
   * There are always going to be several ways to solve these problems, and rarely a “right” answer.

### 5. Reviewing instructor feedback
1. Open your assignment repo on Github
1. Click the Pull Request tab near the top of the page
1. Click the Pull Request named Feedback
1. Review any general comments or other comments visible on Github (more relevant for text files and/or shell)
1. To review comments on your notebook submisison, click the purple ReviewNB button
1. Review the cell-level and general comments from instructor
    * Respond to questions/comments as needed
    * Follow up on anything that is unclear
    * If instructor/TA made a mistake during grading, let them know!
1. Merge the Pull Request on Github to indicate that you've reviewed the feedback and interactive discussion is complete.
