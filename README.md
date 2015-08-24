#Advance Web Application and Design

This is where you will upload all your outputs for the laboratory, assignments and projects.

##What is Git?

Git is a version control software. It is used for tracking changes that you make to your code. It also allows multiple people to work on the same code base. With Git you can easily know which changes were made to your code, you can also revert it to a previous state as long as that state was committed.

##Working with Git

To prepare files to be added into your next commit (staging), you use the `git add` command. 

- `git add .` - adds all the files
- `git add *.html` - adds all html files
- `git add index.html css/style.css` - adds specific files

To commit your changes, you use the `git commit` command. What this does

- `git commit -m "description of what you did in this specific commit"` - directly passing the description by using the `-m` option followed by the description.
- `git commit` - opens up the default text-editor in the terminal and allows you to type a multi-line commit message. 

To upload your changes to Bitbucket use the `git push` command:

```
git push origin master
```

`origin` is the name that you gave to the remote repository.
`master` is the name of the branch that you want to upload. 

In Git you can create branches. Branches allows you to organize your repository into groups. The default branch in Git is called `master`. To create a new branch:

```
git branch NAME-OF-BRANCH
```

To switch to the branch that you created:

```
git checkout NAME-OF-BRANCH
```

To create a new branch and then switch to it immediately:

```
git checkout -b NAME-OF-BRANCH
```

Note that when uploading this branch you have to use its name.

```
git push origin NAME-OF-BRANCH
```


##Working the Repository

For every activity you need to create a new branch in your repository. For example: 

```
git checkout -b activity1
```

In the root of your local repository, open the `Students` folder. Inside the folder, create a new folder with the following format: `LASTNAME, Firstname, MI`. Open that folder and create another folder and name it after the name that you gave to the branch (activity1). This folder is where the files you used for the activity will reside.


