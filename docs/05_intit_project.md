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