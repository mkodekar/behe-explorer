# How to contribute
<hr>
<p>In this secion you will find info o how to contribute,check the index below</p>
### Index

<li><a href="#coding">Coding</a></li>
<li><a href="#pull">Pull requests</a></li>
<li><a href="#">Adding translations</a></li>
<li><a href="#">Feature requests</a></li>
<li><a href="#">Issue reporting</a></li>
<br>
<hr>
<h2 id="#coding">Coding</h2>
<p>Here you will find out how to help us with coding,it takes just a few simple steps.If you're not familiar with Git and GitHub,don't worry.This section describes how to contribute step-by-step.</p>
#### Easy way
<p> For those who are new to this </p>
1. Fork this repository and give it a star if you want
<br>
<br>
2. Go to the 'Code' section of your forked repo
<br>
<br>
3. Select the development branch
<br>
<br>
4. Click 'Download ZIP'
<br>
<br>
5. Extract the downloaded archive
<br>
<br>
6. Install Android Studio.Here you will find a helpful <a href="https://developer.android.com/studio/install.html">tutorial</a>.If you already have it installed,skip this step.
<br>
<br>
7. Now go to Android Studio and select import project (File -> New -> Import project) and search for the directory where you have unzipped the downloaded archive.And wait until it imports
<br>
<br>
8. Now you can edit the code in Android Studio
<br>
<br>

#### Advanced way

<p> For those who are familiar with Git commands </p>
1. Fork this repository and optionally give it a star
<br>
<br>
2. Now create a directory on your computer.This will be our working directory,where code will be downloaded
<br>
<br>
3. Open a terminal in that directry and type ```git init``` (this supposes that you already have Git installed)
<br>
<br>
4. If you had no problems with the last step, type in the terminal (or CMD) ```git remote add origin url```.Remember to replace 'url' with the URL adress of your forked repo
<br>
<br>
5. After it finishes, type in ```git pull origin branch```.Replace 'branch' with the name of the branch (master or development in this case)
<br>
<br>
6. Now you can import the project in Android Studio
<br>
<h2 id="#pull">Create pull request</h2>
<p> For this,you need to have Git installed </p>
1. We suppose that you have already downloaded and imported the project in Android Studio.
<br>
<br>
2. If you haven't already initialized Git in the directory where you have the project,do it.
<br>
<br>
3. Open a terminal in the project directory and type ```git add --all```.
<br>
<br>
4. Now type ```git commit -m "your comment"```
<br>
<br>
5. Now type ```git push origin branch_name```.Replace 'branch_name' with the name of the branch where you want to push the updates.
<br>
<br>
6. To create a pull request,simply go to your repo on  GitHub and compare the branch where you have pushed the updates to the development branch of this repository, addd your comment and submit.
<hr>
<p><b>Issues</b></p>
<hr>
<p>1.When writing the description of the issue please be as explicit as possible</p>
<p>2.Check if your issue haven't alerady been submited!</p>
<hr>
<p><b>Feature requests</b></p>
<p>1.Please post your feature requests in the issue section</p>
<p>2.Explain what do you want/need that feature</p>

