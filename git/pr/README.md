# Ovation Green

Pull requests are used to commit changes to the GitHub repository and track the process of task completion.
Here are the key stages of this process:
1.	Create a branch for a Jira task you receive. 
2.	Make changes in relation to your Jira task and commit these changes. 
3.	Create a pull request, assign reviewers, and request reviews from them.
4.	Receive comments from reviewers, implement the relevant ones, and commit changes (this step repeats as many times as needed to fully complete the task.) 
5.	After reviewers approve your changes, merge your branch with the original branch.
See the following sections for more details.

## Create a branch for a pull request
### Create a branch in GitHub Web
1.	Open the task you are about to start working on in Jira. 
2.	Change the task status to **In progress**. 
3.	In the **To Do** section, **Development** field, click **Create branch**.
![create a branch_1](https://github.com/ovationgreen/scada-readme/assets/150123119/462b1c10-0260-4dcc-9e6e-26f98d0bc6c1)
4.	On the **Create GitHub Branch** page, in the **Repository** field, select the repository to commit the changes to.

_**Note:**_ 

Repositories:

•	_scada-pc_—for storing all source files.

•	_scada-lib_—for storing additional libraries.


5.	In the **Branch from** field, select the original branch for your new branch. 
_**Note:**_ It should be the branch that is named on your Jira task page > **Details** section > **Fix versions**. 
![Fix version](https://github.com/ovationgreen/scada-readme/assets/150123119/ab94aa4e-afbb-45a9-bd08-811e35efd6e7)

6.	In the **Branch name** field, view a proposed name for your branch and change it if needed.

_**Note:**_ 
Follow the `SCADA-0000-Name-of-your-task` name format where 0000 is the number of your JIRA task and Name-of-your-task is its name.

7.	Click **Create branch**.
   
![create a branch_2](https://github.com/ovationgreen/scada-readme/assets/150123119/a64f3bdb-ec71-45a6-b208-fb2c6945df82)

_**Note:**_ 
Click **View branch in GitHub** to open the branch page.

After you successfully create the branch, you will receive a corresponding notification and will be able to view the branch at the page of the related Jira task.
![create a branch_3](https://github.com/ovationgreen/scada-readme/assets/150123119/974731ea-3e26-4b13-9f75-71d96b12ee70)

### Create a branch in GitHub Desktop
1.	In GitHub Desktop, in the **Current branch** tab, open the **Branches** dropdown and select the branch that will become original for your new branch. 
![Create a branch_desktop_1](https://github.com/ovationgreen/scada-readme/assets/150123119/7517c95c-e638-4f28-81f2-69a2a7913a02)

_**Note:**_ It should be the branch that is named on your Jira task page > **Details** section > **Fix versions**. 
![Fix version](https://github.com/ovationgreen/scada-readme/assets/150123119/ab94aa4e-afbb-45a9-bd08-811e35efd6e7)

2.	In the **Fetch origin** tab, make sure that all your files are synchronized.
![Create a branch_desktop_2](https://github.com/ovationgreen/scada-readme/assets/150123119/b4cbde0d-ed56-4488-8f00-31970c54e2db)
3.	On the top panel, click **Branch** and select **New branch…** from the drop-down menu. 
![Create a branch_desktop_3](https://github.com/ovationgreen/scada-readme/assets/150123119/50dfee2a-fec4-4e1e-a66a-33151066fab3)
4.	In the **Create a branch** pop-up window, provide the needed information:

a.	In the **Name** field, provide the name for your branch. 

b.	In the **Create branch based on…** section, select the original branch for your newly created one.

5.	Click **Create branch**.
	
![Create a branch_desktop_4](https://github.com/ovationgreen/scada-readme/assets/150123119/78d4c5af-84c6-40d3-ba9c-f62fbb9d8b7c)

After that, you can publish your branch to a remote repository and start making changes to it.

## Fetch a branch 
_**Note:**_ 
It is only relevant for when you have created a branch in the GitHub web application; when you create a branch in the GitHub desktop application, you fetch files in the process.

Before making any changes, you need to fetch your branch to download all the original branch files from the remote repository to your local repository. 
For that:
1.	Run the **cmd** terminal. 
2.	Type in 'git fetch' and press **Enter** to run the fetch command.

## Check out a branch
_**Note:**_  
It is only relevant for when you have created a branch in the GitHub web application; when you create a branch in the GitHub desktop application, you fetch files in the process.

After your branch is synchronized with the original one, perform the checkout to switch to your new branch for any further changes.
For that, in the **cmd** terminal, type in 'git checkout', insert your branch name from the console, and press **Enter** to run the command. 
Now, the branch is visible in your Workplace source tree and you can work on your task. 

## Create a commit and push changes
When you make the needed changes, you can create a commit and push the changes.
For that:
1.	Open your branch in your Workspace source tree.
2.	In the **Unstaged files** section, click a changed file to review the changes made to your branch in comparison to the original branch.  







```
git lfs install
```

