# Workshop Version Control and Collaborative Development for Research Software

Type-along logs.

**When** 7, 8, 9, 10 October 2024 (third edition)  
**Where** Delft University of Technology  
**Who, the instructors** Halford Dace, Carlos Utrilla Guerrero, Manuel Garcia Alvarez  
**Who, the helpers**  Elviss Dvinskis, Joao Guimaraes, Richard Grimes

---
## 1. Workshop program

### Schedule

Each day we follow the following routine. 
The time slots are not tied to the rolling out of self-contained topics.

| 13:00  | 13:50 | 14:00 | 14:50 | 15:10 | 15:00 | 16:10 | 17:00 | 17:10 |
|:-------|:------|:------|:------|:------|:------|:------|:------|:------|
| Teaching 50' | **Break 10'** | Teaching 50' | **Break 20'** | Teaching 50' | **Break 10'** | Teaching  50'| **Wrap-up 10'** | Closure |

### Content organisation

The workshop is divided into **4 Lessons**, each given in one half a day. 
Each Lesson is further divided into **Episodes**, and then into **Chapters**. 
Unfold the detailed tables of contents in the listing below. 

Continue HERE

<details> 
<summary>
L1. FUNDAMENTAL OPERATIONS WITH GIT
</summary>
  
| Episode | Topic |
|:----|:----|
| **1.1** | **Git repositories for version control** | 
|  | Introduction to Git | 
|  | Git command syntax and getting help | 
|  | Creating an empty repository | 
| **1.2** | **Tracking changes in working documents** | 
|  | Tracking changes with the index | 
|  | Not tracking and stop tracking | 
|  | Undoing changes with the index | 
|  | Deleting and renaming tracked files and directories  | 
| **1.3** | **Organising tracked changes in a history** | 
|  | Committing changes with a configured identity and a message | 
|  | Inspecting changes using the history | 
|  | Undoing changes with the history | 
|  | Marking the history using tags | 

</details>

<details> 
<summary>
L2. BRANCHING AND REMOTE OPERATIONS
</summary>
  
| Episode | Topic |
|:----|:----|
| **2.1** | **Branching** | 
| --- | Create, rename, change, and delete branches | 
| --- | Develop and compare branches | 
| --- | Visualise and merge branches and resolve conflicts | 
| **2.2** | **Operations with remotes** | 
| --- | Create a bare repositories |
| --- | Cloning and pushing to upstreams |
| --- | Syncing changes between repositories |

</details>

<details> 
<summary>
L3. COLLABORATIVE SOFTWARE DEVELOPMENT 
</summary>
  
| Episode | Topic |
|:----|:----|
| **3.1** | **Collaborative Platforms** |
| --- | Connecting to code repositories |
| --- | Exploring the GitHub GUI |
| --- | Collaborating |
| **3.2** | **Collaborative Development for Research Software** |
| --- | Introduction to collaboration in software projects |
| --- | Managing research software projects |
| --- | Organising research teams for collaborative development  |
| **3.3** | Collaborative Workflows |
| --- | Documenting issues |
| --- | Centralise workflow: branching
| --- | Pull requests
| --- | Shared workflow: forking

</details>


<details> 
<summary>
L4. COLLABORATIVE SOFTWARE DEVELOPMENT (to be composed)
</summary>
  
| Episode | Topic |
|:----|:----|
| **4.1** |  **Managing collaboration** |
| --- | Code Reviews |
| --- | Contributing Guidelines |
| **4.2** | **Licensing and Citation** |
| --- | Open Source Licenses |
| --- | Software Citation |
| **4.3** | **Releasing Software** | 
| --- | Semantic Versioning |
| --- | Software Releases |

</details>

---

## 2. Lesson notes

The material of each lesson will be presented in documents named as **Lesson[1234].\*** (the file extension may vary).
The documents are listed at the top of this web page, _above_ this text.
There, bring up the file of your interest upon clicking _exactly on the file name_, hence to the left in the line. 

### 2.1 Lesson 1 and 2: type-along notes

#### During the class
The commands the instructors type on the screen during each lesson will be appended continuously to the documents **Lesson[12].\*** (the file extension may vary).

Please use these lesson notes when you had to lag behind the instructor and need to catch up with the instructions. 

Please refresh the page with the lesson notes in your browser (typically, hit `F5`). 
So, you will view the latest commands as the notes grow.
Kindly notify the instructor if you do not see this happening.

---
## 3. Documents

### The workshop
Please bookmark these URLs for an easy navigation during the workshop:

1. Full URL of this page: https://github.com/4TUResearchData-Carpentries/2024-10-07-gitcodev

### The slides

* Lesson 3, TOC and exercises: [Google Slides](#) (will be updated shortly before the lesson)
* Lesson 4, TOC and exercises: [Google Slides](#) (will be updated shortly before the lesson)

### User Accounts

Register you account via [GitHub account](https://forms.gle/HtVDb6sVjLFgNNnL9)

### The feedback forms

Filling in these anonymous questionnaires is voluntary.
Your honest opinion based on your experience will help us improve the design and delivery of the workshop. 
Thank you in advance for your time.

* Feedback on this workshop: [Google Forms](#) (will be available on the last day)

---
## 4. Resources

### Official Git documentation

* https://www.git-scm.com/docs/
    * Short videos (4-8'): https://www.git-scm.com/videos
    * Reference manual for commands: https://www.git-scm.com/docs
    * General features: https://www.git-scm.com/about
    * ProGit book (505 pages, open access, with full and partial translations in other languages): https://www.git-scm.com/book
    * **Please explore this website**.

### GitHub-related documentation

* [GitHub documentation](https://docs.github.com/en)
* Also Git has a [GitHub account with several repositories](https://github.com/git/)
* Also Linus Torvalds has a [GitHub account with many repositories](https://github.com/torvalds)

### Miscellaneous resources

* Peer-reviewed article: [Five reasons why researchers should learn to love the command line](https://www.nature.com/articles/d41586-021-00263-0) (J.M. Perkel, 2 Feb 2021)
* Blog: [How to undo almost everything in Git](https://github.blog/2015-06-08-how-to-undo-almost-anything-with-git/) (J. Wehner, 8 June 2015)
* Blog: [How to write a Git commit message](https://cbea.ms/git-commit/) (cbeams, 31 Aug 2014)
* Blog: [Ignoring Files and Directories in Git (.gitignore)](https://linuxize.com/post/gitignore-ignoring-files-in-git/) (Linuxize, 25 July 2020)
* Cartoons:
    * [Git commit by xkcd](https://xkcd.com/1296)
    * [Git by xkcd](https://xkcd.com/1597)
    

---

## 5. Licensing

#### Authorship

This course has been designed, developed by Manuel Garcia Alvarez and Giordano Lipari, and delivered by Halford Dace, Carlos Utrilla Guerrero, and Manuel Garcia.

#### Distribution
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a> in accordance with the <a href='https://doi.org/10.5281/zenodo.3516874'> Vision for Research Data & Software management training at TU Delft</a>.
