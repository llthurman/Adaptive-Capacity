# Adaptive-Capacity
# Building a sunburstR plot
Instructions adapted from: 
http://stackoverflow.com/questions/32516366/github-website-publishing-of-knit-generated-html-files-in-rstudio

1. Start with Github
Create a Repository and go directly to Settings (the cogwheel symbol). 
Quick check: under GitHub Pages, look for the message: "Your site is published at http://...github.io/[sitename]". In my case the address is https://llthurman.github.io/Adaptive-Capacity Now you can go to your browser, type the address and see that a new site has been born (caution: sometimes this takes minutes to materialize).

2. Now it's time to go to RStudio. 
Start a New Project from the pull-down menu. Choose Version Control. Click on the GIT symbol ("Git Clone a project from a Git repository"). Mine is called Sunburst. Under Repository URL we need to enter the Repository URL (https://github.com/llthurman/Adaptive-Capacity) The rest is not critical. Press on Create Project.

3. Create a new R Markdown document. 
Give it a name. You are the author. Select HTML. Click OK. Now you can modify, add, or just leave what popped-up on the screen as is to finish up the demonstration. Press on the top menu where you see a knitting pin (Knit HTML), give it a name and save the document. Whatever you name it, it has to end in .Rmd (case sensitive). 

4. Pushing work to GitHub.
First, click on the GiT symbol on the top menu (above "knit HTML" depending on the configuration of your RStudio). Select Commit. You can select any file you want to upload. Post an ultra-short note under "Commit message", e.g. the date/time of update. Click on the Commit button. Now you are ready to click on Push. You will be prompted to enter your Github account Username and Password. 

5. Back to GitHub.
Refresh the page displaying your repository. You should now see the additional documents, including [filename].html
Quick check: Go to your browser and enter in the URL bar what for me would be https://llthurman.github.io/Adaptive-Capacity and then just tag on the name of the html document you created in RStudio.

