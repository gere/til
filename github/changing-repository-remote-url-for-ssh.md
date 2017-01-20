# Changing the remote url of a repository for SSH

Once you have set up your ssh keys, you have to set or change the remote repository URL as follows:
```bash
$ git remote set-url origin git@github.com:gere/til.git
```
Using the HTTPS url suggested by GitHub when you create a new repository, for example https://github.com/gere/til.git/, results in an authentication error.