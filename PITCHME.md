
# git and github

Niall O'Gorman


---

### who has used these source control systems?

<img src="./pics/IBM-ClearCase.png" width="250">
<img src="./pics/Subversion_Logo.png" width="300"> 
<img src="./pics/VS-TFS.png" width="300">
<img src="./pics/cvs.jpg" width="300">
<img src="./pics/mercurial-logo.png" width="300">
<img src="./pics/vss6.jpg" width="250">

---

### or perhaps

<img src="./pics/sclm.jpg"/>

---
### this guy had other ideas

<img src="./pics/linus-torvalds.png"/>

---

<img src="./pics/linus.jpg">

---


<img src="./pics/Git-Logo-2Color.png" alt="git" width="500"/>
<img src="./pics/github-octocat.png" alt="github" width="500"/>

---

```
git push
```

simple, elegant, powerful

+++

<img src="./pics/pipeline.png" />

---

### the git ecosystem 

- 117K businesses <!-- .element: class="fragment" -->

- 61M repositories <!-- .element: class="fragment" -->

- 22M developers <!-- .element: class="fragment" -->

+++

### supporting all these technologies and many more

<img src="./pics/supporting-logos.png">

---

### go on then, tell me about git...

<img src="./pics/Git-Logo-2Color.png">
 
+++

- distributed version control system - __each developer has full history locally__

- non linear workflows - __branches are cheap, rapid branching and merging__ <!-- .element: class="fragment" -->
 
- optimized for performance - __efficient for large projects__ <!-- .element: class="fragment" -->

- data integrity - __cryptographic authentication of objects in git repository (commit hash)__ <!-- .element: class="fragment" -->

- toolkit design - __designed to support frontends, open source, chain components__ <!-- .element: class="fragment" -->

---

### and github ? 


<img src="./pics/github-octocat.png" alt="github"/>

+++

- git hosting service with web based gui

- access control - __code security__ <!-- .element: class="fragment" -->

- bug tracking, issues management <!-- .element: class="fragment" -->

- pull requests <!-- .element: class="fragment" -->

- commit history <!-- .element: class="fragment" -->

- collaboration platform - __social media-like features (feeds, wikis), fork request__ <!-- .element: class="fragment" -->

- 3rd party integration - __Jenkins, Pivotal tracker etc__ <!-- .element: class="fragment" -->

---

### Ways to use git

+++

command line

+++

IDE integration

---

## workflows
* getting started
* version control
* branches
* delivery
* undoing

---

## workflows
* `getting started`
* version control
* branches
* delivery
* undoing

+++

- create new repo on github

+++

<img src="./pics/gitNewRepo.png">

+++

```
git clone
```
copy the repository to local working directory
---

## workflows
* getting started
* `version control`
* branches
* delivery
* undoing

+++

<img src="./pics/gitaddcommit.png">

+++

```
git add
```
stage changes for next commit

**useful when making lots of change and reviewings**

+++

```
git commit
```

- commit staged snapshot (with message) to project history

- **commiting changes are always to local repository**

+++

### tips

* use `git stash` and `git stash pop` to temporarily save changes

* create `.gitignore` file to specify files which are not part of project

---
## workflows
* getting started
* version control
* `branches`
* delivery
* undoing

+++

<img src="./pics/branches.png">

+++

master branch - *production ready, dont develop in master*

big feature - used to implement an application features, multiple commits

little feature - minor changes, used to fix bugs, few commits

+++

```
git checkout <branch>
git checkout -b <new branch>

```
navigate between branches

+++

```
git merge <branch>

```
pull changes in branches together

+++

merge type #1  - ___**fast forward merge**___

+++

<img src="./pics/ffwdmerge1.png">

+++

<img src="./pics/ffwdmerge2.png">
- instead of "merging" git can move the head of the branch to target

+++

merge type #2 - ___**3-way merge**___

+++

<img src="./pics/3waymerge1.png">
- branches have diverged so fast forward not possible

+++

<img src="./pics/3waymerge2.png">
- git algorithm uses common ancestor and will auto merge or flag any conflicts

---
## workflows
- getting started
- version control
- branches
- `delivery`
- undoing

+++

```
git pull 

```
fetch remote copy and merge into local

+++

```
git push

```
transfer local commits to remote

---
## workflows
- getting started
- version control
- branches
- delivery
- `undoing`

+++

when you need to fix stuff

+++

```
git checkout
```

checkout a branch, a file or a commit

+++


```
git revert
```

add a new commit to undo a commit

+++

```
git reset
```

use only for local changes! permanent undo, no way to retrieve original

+++

```
rm -rf
git clone
```

the **nuclear** option, blow everything away and restore local repository from remote

---

questions?

---


- https://github.allstate.com/
- https://www.atlassian.com/git/tutorials/
- http://www.drdobbs.com/tools/three-way-merging-a-look-under-the-hood/240164902


