# Work with trafficking data and create a user interface in R using RStudio and Shiny

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio.png"/>](https://www.rstudio.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/shiny.png"/>](https://shiny.rstudio.com/)

## Instructions:

### Step 1.  Log into your [http://datascience.ibm.com/](http://datascience.ibm.com/) account, then click the hamburger icon in the top left and select RStudio.

> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-select.png"/>

### Step 2.  Create a new project by clicking on `File` > `New Project`.

> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-new-project.png"/>

### Step 3.  Select `Version Control`.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-new-version-control-project.png"/>

### Step 4.  Select `Git`.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-select-git-project.png"/>

### Step 5.  Fill in git repository details using the URL `https://github.com/Davin-IBM/Proof-of-Technology` and press `Create Project`.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-git-project.png"/>

After the project gets created, you'll see a screen similar to the following:

> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-project-created.png"/>

## Step 6.  In the files pane in the lower right of the RStudio IDE, click `DSX`, then click `Lab-3`.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-files.png"/>

## Step 7.  Click the `connection.R` file and fill in your dashDB connection details.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-connection.png"/>

## Step 8.  Click the `dashConnectAndInteractInR.R` file in the files pane in the lower right of the RStudio IDE and run the cells in sequence from top to bottom in the notebook using the `Run current chunk` (green triangle) button in the top right of each cell.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-notebook.png"/>

## Step 9.  Click the `app.R` file in the files pane in the lower right of the RStudio IDE
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-shiny-app.png"/>

## Step 10.  Click the `Run App` (green triangle) in the top right of the main panel to run the app.  The app will appear in the Viewer pane in the bottom right corner of the IDE.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-app-viewer.png"/>

Consider this notebook your data playground.  This is the place where you can test out new ideas, connect and fuse various data sets and try out different visualizations.  If you're happy with something in your notebook, then go ahead and make it available to interact with in your app.

## Step 11.  Click the little black downward pointing triangle next to the  `Run App` (green triangle) in the top right of the main panel to run the app in another browser window.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-app-external.png"/>

## Step 12.  In the running app, click on some of the rows in the table and vet some of the records.
> <img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/Lab-3/images/RStudio-lab3-vet-records.png"/>

Notice how your app reacts to the user.  Try out the search in the upper right corner.  Try the filters above the various columns.  Click on the items in the pie graph legend as well as the various wedges in the pie.   Click on some of the rows in the table and save your vettings.  As the vettings are saved, they are persisted back to dashDB (you can verify this yourself by queying your dash instance).  Now, go back to your Lab-2 notebook and re-run the ML predictions and see the changes reflected there, in dashDB and in the UI (you'll need to restart your shiny app to pick up the changes).

### Step 13.  [Get Inspired!](https://shiny.rstudio.com/gallery/)

You now have an end-to-end skeleton application that uses vetting data, dashDB, Spark and DSX that you can now flesh out into something truly useful in a short amount of time without having to write a lot of code.
