# Quotes
A Repository of quotes

## Getting Started


#### 1. Clone this Repository <br> 
**a)** Click on the `<> Code` tab of this repo and copy the HTTPS url. <br>
![image](https://user-images.githubusercontent.com/79658062/114715615-43071d80-9d01-11eb-941f-92361d5cb52a.png)

**b)** Open GitHub Desktop and select `File > Clone repository...` <br><br>
<img src ="https://user-images.githubusercontent.com/79658062/114715489-1ce17d80-9d01-11eb-9167-dd3a11de3c43.png" width = 60%>

**c)** In the `Clone a repository` menu, paste the URL you copied in Step 1 and set the local path to C:\src\Quotes **then click Clone** <br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114716164-c88acd80-9d01-11eb-8539-6c1287576614.png" width = 60%>

#### 2. Fetch and Pull any Remote Changes <br> 
**a)** Make sure your current repository is set to this repository called `Quotes`. Make sure your current branch is set to main. Then click the `Fetch Origin` button in the top right. <br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114717457-0cca9d80-9d03-11eb-84f5-e6e57bb6b269.png" width = 60%>


**b)** If your `Fetch Origin` tab transforms into a `Pull origin` tab, click the tab again to pull changes from remote. The 2 with a down arrow next to it means that I am 2 commits behind the remote branch called `main`.  <br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114719038-a0e93480-9d04-11eb-962b-25eac7b861ff.png" width = 60%>

#### 3. Open repo in file system<br> 
**a)** Select `Repository > Show in Explorer` <br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114719605-41d7ef80-9d05-11eb-920d-19ea6b99ec56.png" width = 60%>

**b)** You should now see the repository in the file explorer and the `FavouriteQuotes.txt` file <br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114720108-b90d8380-9d05-11eb-806b-f35745d24b3a.png" width = 75%>

#### 4. Add your favorite quote to FavoriteQuote.txt!<br> 
**a)** Open `FavoriteQuote.txt` and on a new line, add your favourite quote along with its author. Then **save the file**! <br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114720608-291c0980-9d06-11eb-9ef8-58235fc1e3db.png" width = 60%>

**b)** Open GitHub Desktop again. Under the `Changes` tab, you should see the new file change you have made along with its content. You will notice on the right a view of the changes you made to the file. This is called a **diff**. The annotation means  the following:
```diff 
+ new content that has been added
- content that has been removed/modified
```
<br><br> 
<img src ="https://user-images.githubusercontent.com/79658062/114722329-b449cf00-9d07-11eb-86ec-3ae7da435114.png" width = 60%>

#### 5. Create a new branch<br> 
**a)** Select `Current Branch` and in the dialog box that pops up, type **`Your_First_Name/my-quote`**. This is will be the name of your branch. Then select `New Branch` and if prompted select `create branch`. Then select **`Bring my changes to <branch name>`**. Lastly, click `Switch branch` <br><br> 

![image](https://user-images.githubusercontent.com/79658062/114723258-8913af80-9d08-11eb-8be9-f0405a1c380d.png)
<br>
![image](https://user-images.githubusercontent.com/79658062/114723286-8e70fa00-9d08-11eb-96d8-ff24a9cfe417.png)
<br>

**b)** You will now notice that your current branch will be your_first_name/my-quote
<img src ="https://user-images.githubusercontent.com/79658062/114723511-b6f8f400-9d08-11eb-8570-dfc6c8b8c0ef.png" width = 60%>

#### 6. Commit Changes<br> 
**a)** Now we will bundle our change(s) together into a commit. Make sure FavoriteQuotes.txt is checked in the side pane. Add a title to the commit and a description if you would like. Lastly hit the commit button in the bottom left to add the commit to your branch.<br><br>
<img src ="https://user-images.githubusercontent.com/79658062/114724205-528a6480-9d09-11eb-89cb-3aa7a685d587.png" height = 40%>

**a)** In the top right, select `Publish branch`. This will publish the branch and push it to GitHub. On GitHub, you should see your branch listed under `branches`

![image](https://user-images.githubusercontent.com/79658062/114724571-b1e87480-9d09-11eb-97f1-356c585d7e19.png)

#### 7. Create Pull Request<br> 

**a)** Now that we have pushed our branch along with its commits to our remote repo (hosted on GitHub), we are now going to open a Pull Request so that the team can review our changes and allow us to merge onto the main branch.<br>

**b)** In GitHub, navigate to the `Pull requests` tab in the repo. Then select `New pull request` <br>

![image](https://user-images.githubusercontent.com/79658062/114725673-ae092200-9d0a-11eb-8713-529e4768e606.png)

**c)** In the Comparing changes menu, make sure the base branch is set to `main` and the `compare` branch is set to the branch you created in the previous step. <br>

![image](https://user-images.githubusercontent.com/79658062/114726168-21129880-9d0b-11eb-95f8-93c3bdc1dd1e.png)


**d)** At this point you should see something like the image below. Select `Create pull request`<br>

![image](https://user-images.githubusercontent.com/79658062/114726543-7cdd2180-9d0b-11eb-821e-7f7ac198a2a7.png)<br>


**Just a Note:** As we can see in the screenshot in step 7. b), GitHub already detects that our branch has had recent pushes and prompts us to open a Pull Request. Hence we could have also selected `Compare & pull request` as an alternative which would have skipped steps b through d.

**e)** At this point we should see the `Open a Pull request` menu. **Update the Pull Request title** so that reviewers have a one line summary of the change. **Update the description** if you would like.
**Set the reviewer** to one, or both of the repo owners (either Mayha, Kyler or both). This will notify us of your Pull Request once you create it. **Assign yourself to the Pull Request** under the Asignees section. **Add the label `called new-quote`** under the Labels section. Lastly click **`Create pull request`**

![image](https://user-images.githubusercontent.com/79658062/114727389-2b816200-9d0c-11eb-872a-f106b434d393.png)



