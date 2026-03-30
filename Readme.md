<centre><H1>How i added my Local Folder named "level 1" which is level 1 of CSS learning on Github on a repo<H1><Centre>

<Br>1) <b>First i made the folder which is on in Worksration in my pc a git folder<b>
<br>- first i went to folder which i want to upload
<br>- then i an a command "git init" 
<br>- this cmd makes my folder to track on git 
<br>- due to this a .gif file is generated 
<br>- .git files is hidden file to to see this type of files i ran cmd "ls -hidden"
<br>- this shoes me .git file means folder "Level 1" is now on tracking

<Br><b>2) Now next i did was I created a Repo in github with any name, i named it "CSS-Learning"<b>

<Br>3) <b>than to connect the "Level 1" folder to our "CSS-Learning" Repo<b> 
<br>- I ran commmand " git remote add origin Link"
<br> Here intead of link i paste the link of the repo i hsve just created 
<br>- This command links the Repo to folder and we named the repo as "origin" we can neme what ever we want , insted of Pasting link each time we just type name of repos that is "origin" 

<br><b>3) Check Branch
<br>- I ran a command "git branch" 
<br>- It shows me the branch we are at, meaning when we will upload any file or code i.e push code to reop it will goes in this branch
<br>- it shows me the brach is "master"
<br>-But now a days the master branche is called and recoganized as "main" so now we have to rename brach to "main"
<br>- For this we ran a command "git branch -m main"
<br>-  nor we are at main branh as after running "git branch" it is now showing "main" 

<br><b>4) Now the "Level 1" folder is traked or connnected but the files in the folder are still untracked <b>
<br>- But how did i now that the filed are untradked i) at the front of file name in code editor VS code the sign "U" indicates Untracked ii) we ran a command "git status" this cmd shows which files are tracked and which is commited which is untracked 

<br><b>5) to add this files i.e "index.html" & "style.css" we ran a command "git add file name" i.e "git add index.html" and .. <b>
<br> but if we have more than one files no need to add seperate files , we can add all files at once using "git add ."

<br><b>6) now we were again ran command "git status" it is showin now added but now commited means now officially tracked we just ( like we write something in notepad this is like add and we same it using CTRL+S means saved this is Commit ) <b>
<br>- to commit changes or to official save we ran a command "git commit -m "Message or name of change" 
<br>this comand is conmits the changes after we ran "git status" it will show the branch name and noting to commit  

<br><b>6) now remember this is commited but now in Github repo "CSS-Learing" <b>
-



