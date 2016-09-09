Hello,

To collaboratively code will require us to be able to write code on different machines,
and then combine our separate work into a single working code base to download onto the robot.

We will use github to facilitate this information. The first task will be to create a Pull Request
editing this document and adding your name to the bottom. These are the steps you will take to do this.

1) Make sure you have github command line downloaded locally. 
This can be found here (https://git-scm.com/downloads). Install with the default settings, then launch git bash. 

2) clone this repository to a local folder on your machine.
In git bash, use the command `git clone https://github.com/FRC-Team-399-EagleRobotics/FRC399-2017-Preseason.git`
You now should have a folder called FRC399-2017-Preseason. You could view all folders using the command `ls` 
Change into the folder using `cd FRC399-2017-Preseason` (after you type FRC399, you can hit tab to autocomplete the rest)

3) You are now in our collaborative folder. you can see the status by typing `git status`
Now you want to create a personalized branch called MyNameBranch (replace MyName with your name!)
This is done by the commands `git branch MyNameBranch` followed by `git checkout MyNameBranch`

4) Now you can edit the document and add your name. use `pwd` to find where your file is, then open file finder and edit the text file collaborators.txt to add your name

5) add and commit your changes. This is done with `git add collaborators.txt` followed by `git commit -m 'Added my name'`

6) push your code to the central repo `git push origin MyNameBranch`. You will have to enter your github credentials at this step.

7) go to the browser, find your branch on the repo, and create a pull request. Congrats! you did it. 
