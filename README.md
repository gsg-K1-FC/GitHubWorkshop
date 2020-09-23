# GitHubWorkshop 

This exercise Will help you to become more familiar with Git and GitHub. :octocat:


## What should you do? :thinking: 

### Step 1: Clone repo and open it using VSCode 

- Clone this repo to your local machine using git bash:
```shell
$ git clone https://github.com/gsg-K1-FC/GitHubWorkshop.git
```

- Then change the directory to our project.
```shell
$ cd GitHubWorkshop
```

- Open the project on VSCode
```shell
$ code .
```

---
### Step 2: Create a new issue and a branch :star2:

- Create a new isuue in this repo with the title `fix my page`, then assign it to yourself.

- Create a new branch with `your name` using git bash. for example:
```shell
$ git checkout -b sahar
```

---
### Step 3: Task :boom:

- Make the followings edits on `index.html` file:

  - Change the `Student Page` header to `yourname`.for example:
  ```html
  <h2 class="studentName">Sahar's Page</h2>
  ```
  
 
    - Add more info about you in `about me` section (you can use the project that you have built in session01).

---
### Step 4: Add the new files to the staging area and commit your changs. :muscle:
- Check status.
```shell
$ git status
```

- Add the modified file to the staging area.
 ```shell
$ git add index.html
```

- Commit your changes and make a reference to your issue number.
  - for example, if your issue number is 50 the commit should be like this:
```shell
$ git commit -m 'fix my page #50'
```
---
### Step 5: Push your branch to github :relieved:

- To check your branches you can use this command:
```shell
$ git branch
```
- the branch that you are working on should be the green one as shown in the figure below:
![](https://i.imgur.com/Hsj8ICW.png)

- Push your changes to your branch.
```shell
$ git push origin <your branch name>
```

---

### Step 6: Create a Pull Request :heavy_check_mark:

- Create a pull request on github.
-  assign `saharAdem` and `rahaf-96` as a reviewers.

:exclamation: **Warning: Don't Merge the pull request**

---
**NOTE:The exercise must be submitted before 27/09/2020.** <br/>
**GOOD LUCK** :v: :sparkles:

