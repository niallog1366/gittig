
# git and github

Niall O'Gorman


---
Version control solutions

<img src="./pics/IBM-ClearCase.png" width="250">
<img src="./pics/Subversion_Logo.svg.png" width="300">
<img src="./pics/VS-TFS.png" width="300">
<img src="./pics/cvs.jpg" width="300">
<img src="./pics/mercurial-logo.png" width="300">
<img src="./pics/vss6.jpg" width="250">

---

<img src="./pics/Git-Logo-2Color.png" alt="git" width="500"/>
<img src="./pics/github-octocat.png" alt="github" width="500"/>

---

```
git push
```

simple, elegant, powerful

---

## so what is git? and how do we use it?
 
---

<img src="./pics/Git-Logo-2Color.png">
 
+++

distributed version control system
optimized for performance |
security - cryptography to store all objects in git repository |
open source, standard |


+++

-diagram

---


<img src="./pics/github-octocat.png" alt="github"/>

+++

git hosting service with web based gui

access control |

collaboration platform |

3rd party integration |

---

How to use git

+++

command line

+++

IDE integration

---

## workflows
- getting started
- version control
- branches
- delivery
- undoing

---

## workflows
- __***getting started***__
- version control
- branches
- delivery
- undoing

---

- create new repo on github

+++

<img src="./pics/gitNewRepo.png">

+++

```
git clone
```
---

## workflows
- getting started
- __***version control***__
- branches
- delivery
- undoing

+++

<img src="./pics/gitaddcommit.png">

+++

**commiting changes are always to local repository**

---
## workflows
- getting started
- version control
- __***branches***__
- delivery
- undoing

+++

<img src="./pics/branches.svg">


+++

master branch - *production ready, dont develop in master*

big features - used to implement an applicaiton features, multiple commits

little feature - used to fix bug, few commits

+++

fast forward merge

<img src="./pics/beforemerge.svg">

+++

3-way merge
<img src="./pics/beforemerge2.svg">


---
## workflows
- getting started
- version control
- branches
- __***delivery***__
- undoing

+++

delivery
- git fetch
- git pull
- git push
- .gitignore

---
## workflows
- getting started
- version control
- branches
- delivery
- __***undoing***__

+++

fixing stuff
- git checkout - checkout a branch, a file or a commit
- git revert - add a new commit to undo a commit
- git reset - only for local changes! permenant undo, no way to retrieve original 
