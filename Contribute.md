# Dristi : A guide for college freshers - Contributions

## Prerequisite
* [Git](https://git-scm.com/downloads) 
* [Android Studio](https://bit.ly/3RXrm88)
* [Firebase](https://firebase.google.com/)

## Local Setup 💻

- Fork this repo (button on top)
- Clone on your local machine

```terminal
git clone https://github.com/example
```
- Navigate to project directory.
```terminal
cd Hacktoberfest2022
```

- Create a new Branch

```markdown
git checkout -b my-new-branch
```

- Commit your changes.

```markdown
git commit -m "Issue or feature resolved"
```
- Then push 
```markdown
git push origin my-new-branch
```


- Create a new pull request from your forked repository

<br>

## Avoid Conflicts {Syncing your fork}

An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.   

```terminal
git remote add upstream https://github.com/fineanmol/Hacktoberfest2022
```

You can verify that the new remote has been added by typing
```terminal
git remote -v
```

To pull any new changes from your parent repo simply run
```terminal
git merge upstream/master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.

For more information on syncing forks [read this article from Github](https://help.github.com/articles/syncing-a-fork/).


## Running the project
1. After Forking and cloning this Repository to your local machine 
2. Open Android Studio -> Go to the *file* tab (Top Left) -> Click on *Open Project*
3. Choose the folder where you cloned the project (eg.D/Hacktoberfest2022)
4. Choose the folder and click "*open*"
5. Android Studio will give you a warning stating **Trust Project** Click **"Trust"**
   <h4> Wohoo! You are now ready to Contribute 😀 </h4>

## Creating a PR
So After making the changes or updating any features of the app you have to make a PR (Pull Request) <br>
to do this watch this **[Video](www.youtube.com)**

<!-- ## Recent updates
[Mention any updates]

## Any Other Info needed for the Contributions.
 -->
