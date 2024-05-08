# Setting up Git and Github

## Git Installation

- In Debian based systems, install git by the command `sudo apt install git`.
- Usually, most of the Linux systems comes with git pre-installed.
- In windows, download the installer from [(https://gitforwindows.org/)](https://gitforwindows.org/). Run it with administrator privileges. Accept the default values and choose Windows Command Prompt for accessing git.
- Verify the installation by `git --version` in terminal/Command Prompt
- Once you installed `git` define global username and mail ID from terminal or command prompt.
  
```
$ git config --global user.name "Your Name"   
$ git config --global user.email "your@mail.id"
```

## Github Account and `gh-cli`

- the account registration with github.com is straightforward
- for safety it is recommended to use `github-cli`. You can download the binaries from here: [https://cli.github.com/](https://cli.github.com/)
- it can be used without `github-cli` however the process is time consuming and you have to create tokens and save it locally in your machine.
- once it is installed authenticate it using `gh auth login`
- once you authenticated through the browser you can access your github repositories from terminal without need to use browser or app