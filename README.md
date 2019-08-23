# GIT-Tutorial

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>GIT Tutorial</title>
</head>

<body>
    <!-- https://youtu.be/oFYyTZwMyAg
    
    This is the video that I learned about GIT and that I will use to add more info to this page using the git workflow and adding it to the github page. Mainly will want to use this video to add images from the conflict part of the video to explain that in this repo.-->

    <div class="header">
        <h1>GIT tutorial</h1>
        <p>In this tutorial I will be going over 5 of the easiest GIT comands to learn.</p>
    </div>
    <div class="main">
        <h3>git pull</h3>
        <p>
                The 'git pull' command is going to make sure you pull in any and all changes that were made to the master
                branch. After confirming the
                files are up to date you can make any changes or continue working on what you planned to do.</p>
        <img src="img/git-pull.png" alt="git-pull">
        

        <h3>git add</h3>
        <img src="img/git-add.png" alt="git-add">
        <p>The 'git add &lt;filename&gt;' command will save that files changes made so that they can be pulled up again
            if something
            happens and they can be committed at any point.<br />
            You can put an -A or * to make sure <i>all</i> the changes are being added into staging.</p>

        <h3>git commit</h3>
        <p>The 'git commit -m "commit message"' command will add
                all the changes made to <b><u>Staging</u></b>. <b><u>Staging</u></b> means they are ready to be merged to
                the master branch.<br /> The -m "" means
                commit message. You will want explain this commit in as much detail as possible with as little words
                as possible.<br />
                You can also use 'git commit -A' to commit any files you've added with 'git add', and also commit any files
                you've changed since then</p>
        <img src="img/git-commit.png" alt="git-commit">
        

        <h3>git push</h3>
        <p>the last command you will use is the 'git push' command. That will take your changes from staging and
                merge them with the master branch. </p>
        <img src="img/git-push.png" alt="git-push">
        

        <h3>git status</h3>
        <p>the 'git status' command will give you a list of files you've changed and those you still need to add or commit or will let you know your branch is up to date.</p>
        <img src="img/git-status-after-merging.png" alt="git-status">
       
        <p>Below is the shot if you were to type 'git status' after making your initial changes to your files. It is basically saying the file in red was edited but you did not 'git add' this file.</p>
        <img src="img/git-status-after-initial-edit.png" alt="">
        <p>Below is the shot if you were to type 'git status' after you 'git add' your files. It is basically saying the files in green have been added and saved and they are ready to be comitted.</p>
        <img src="img/git-status-after-adding-changes-to-staging.png" alt="">
        <p>if you 'git status' after commiting your changes you wil get a "Your branch is up to date" message letting you know your file ws committed and merged to the master branch.</p>
        <img src="img/git-status-after-merging.png" alt="">
        
        
        
    </div>
</body>

</html>
