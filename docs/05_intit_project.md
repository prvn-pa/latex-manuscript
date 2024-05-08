# Setting up your manuscript repository

Go to your preferred folder, where you're planning to keep your manuscript file. Now, follow these steps:

## Creating and cloning repo

- Create a github repo by `gh repo create username/repo-name --private` here the `username` is your github user name and `repo-name` is the name you want to give your repo. `--private` tag ensures that the repo can be accessed only by you or by the persons who you invite.
- then clone the repo to your local machine by `gh repo clone username/repo-name`
- you may get a warning that you cloned an empty directory - you can safely ignore it, because hereafter only you're going to add the files

## Creating the `.tex` file

- now open VS Code and the File > Open Folder ... Navigate to the `repo-name` and open it
- In the `Explorer` tab, click the `New File` icon and create a file `manuscript.tex`
- Double click the file to open on the right side editor
- this is our manuscript file and here is we are going to write our manuscript

## Adding dummy text and sync with github

- to learn sync with github, add a dummy text to the file for example:

```
aaaaaaaaaaaaaaaaaaaaaaa
```

-save it
- now you can see a number badge on the left panel, source control
- click that icon, you could see a message box, followed by commit button and a list of changes
- in the message box type a readable message like `files initiated` and click commit
- the message is crucial, because if you want to switch back to particular version later you can directly read the commit message and switch to it. If you use same message for different commits it would be hard to locate you version of interest
- now click the `Sync` option to sync with github account. if you open your github repository in the browser you should see the updated file.

## Alternate ways to sync

- even without VS Code, you can commit and sync with github (however gh-cli is essential to clone and push)
- to do that, first add the files to git tracking by `git add .` this will add all the files
- then commit it by `git commit -m 'files initiated`
- finally, sync to github by `git push origin main` or simply `git push` 

## Add only selected files

- when compiling the tex file it would produce log files and auxilary files. which you often no required to sync with the cloud.
- you can safely ignore these files by creating a `.gitignore` file.
- click add a new file and name it as `.gitignore` - note the `.` prior to the name
- open the file and add the extension of files you wish to exclude from sync

```
# the following files has to be ignored

.log
.aux
```

- save and sync