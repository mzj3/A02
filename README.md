# A02
**How to use Github and GIT**
  
  **Github** is a company that provides hosting for software development version control using GIT.
  GIT itself is actually a protocol used as a version control system that lets you manage and keep 
  track of your source code history. We will be using GIT _by_ using Github, meaning that GIT is 
  never directly used. It's all done through Github. <br>
      
  Firstly, you'll want to make a Github account. This will allow to view an unlimited amount of   
  public and private repositories on GitHubs website. Making an account is free, it you only need  
  to upgrade if you plan on working on a private project that includes more than 3 collaborators.<br>
    
  For this tutorial, I will not be installing **GIT** on the system localy, but I will go in
  detail if you wished to do so. Git was originally created by OS founding father Linus Torvald, 
  the creator of Linux. He originally made it to track his changes as he was developing Linux, and
  it soon exploded as a simple and powerful way for programmers to collaborate, coordinate work,
  and work together on code and development projects. Git allows teams to work **remotely**. If you 
  wish to install GIT on your machine, here is a link to the download for Linux, Mac, and Windows.
  * https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

  Now that you know what GIT is and have a proper Github account setup, it's time to make our first 
  repository. A **repository** (or repo) is essentially synonymous with the word “project.” This repo can
  consist of everything including images, files, spreadsheets, videos, and more. It is good practice
  to include a README file that allows users to have an idea what the repository is all about. For
  example, this README.md file exists for the assignment A02 for the class IS-117. It's purpose is 
  to explain to the reader what the project is about. README's can be added at the time of repo
  creation, or sometime after.

  To create the repo, hit “new repository” in the upper-right-hand corner. This will lead you to a 
  screen where you can name the repo, include a description, as well the optional auto-generated
  READMe file. Then click "Create Repository".

  Now that you have a repo, you can now create a branch. **Branches** allow a user to make different 
  versions of their project. This means you can make risky changes without ruining the original 
  version of your project. A master/main branch is what acts as the final product, or the branch that 
  is most complete/stable. When you create a branch, it will copy the main branch. Typically, a
  branch typically goes through many steps and approvals before it is ever merged into the main 
  branch. Branches are ideal for new features or bug fixes.

  To create a branch, go to your brand new repo and click the dropdown that says "branch: main".
  Type the name of a new branch, and click "Create Branch". 
    
  We now have a repository and a new branch. The next step is to create and **commit** changes to a specific
  branch. Lets say we go to our new branch called "branch: test". If you click the pen icon when viewing
  a file, you are able to edit it on Github. From here, you are able to make necessary changes and edits.
  You can now save your edits by writing a commit message and clicking "Commit Changes". Commits give a
  reason why a specific change was made. It is important to write something down anytime you make a
  change. Commits give a history of changes and helps communicate to collaborators how the project has
  evolved over time.

  If a user wants a branch to be merged into another branch, they must create a **pull request**. A pull 
  request is necessary when notifying other users in the project that you wish to incorporate your code
  into the main branch. A pull request will compare and contrast what has been added and removed in the
  code with green and red highlights. These requests are commonly done alongside a commit. It is important
  to use the '@' feature to notify collaborators whose code may be effected by these chanegs.

  In order to create the pull request, go to "pull request" tab and press "create new pull request". This
  will then compare the "branch: test" and "branch: main". If you are satisfied with the changes, be sure
  to press "create pull request.".

  Lastly, you'll want to **merge** your pull request to the main branch. This can vary on from project to 
  project. If you are the leader or doing a project by yourself, you have the green light to merge to main.
  Otherwise, it's important to contact your superiors to handle it. If you wish to merge, simply hit the 
  button that says “merge pull request,” select “confirm merge”. You are now free to delete the branch 
  named "branch: test".
  
**PART 1**: Directions on Using Webstorm.

  Webstorm WebStorm is a cross-platform IDE that provides consistent experience on the Windows, macOS, 
  and Linux operating systems. It can be used for coding JavaScript and its related technologies, including 
  TypeScript, React, Vue, Angular, Node.js, HTML, and style sheets. Similar to other IDEs, WebStorm makes 
  your development experience easier, automating routine work and helping you handle complex tasks with ease.

  First I will be going over the installation. In order to Install WebStorm, it is highly reccomended to 
  install the Toolbox App to access all JetBrains products. Download the installer .exe from the Toolbox 
  App web page and follow the install wizard. 
  * https://www.jetbrains.com/toolbox/app/

  Here we will installing WebStorm.
  ![image](https://github.com/mzj3/A02/assets/98351089/295fa5d5-6411-421a-b0d1-c73a30dba349)
  If you want a specific version, click "Avaliable Versions". Make sure to log-in with yout JetBrains account
  as this IDE is not free and requires a valid license. You can now open WebStorm through the Toolbox App.

  Now that WebStorm is installed on your machine, we can go through some basics. A project inside of WebStorm
  is a folder that holds all of the source code that you write, as well as the libraries, tools, and app
  configuration files. There is an auto-generated folder called ._idea_ that is used for configurations and 
  version control systems (such as GIT) You can open, check out, and create projects from the WebStorm 
  Welcome screen.
  ![image](https://github.com/mzj3/A02/assets/98351089/aca03299-24cf-45ce-8611-0cb692effcc3)
    Click _Open_ > _NameOfProjectFolder_!

  To create a new projects, simply click "Create New Project" on the Welcome Screen or
    Click _File_ > _New_ > _Project_
  Next, choose "Empty Project". On the right side, choose the application folder and choose "Create".

  Now that a project exists, we can create a file. Choose new from the context menu of the selection and
  choose the desired file type. This can be HTML, Stylesheet, or JavaScript. In this class, we will be focussing
  on HTML and CSS, so I reccomend the first two options.
  ![image](https://github.com/mzj3/A02/assets/98351089/9745ad71-6c7a-4478-b1ff-1dae24dc38c5)

**Part 2**: Glossary
* **Branch** - 
* **Clone** -
* **Commit** -
* **Fetch** -
* **GIT** - test
* **Github** -
* **Merge** -
* **Merge Conflict** -
* **Push** -
* **Pull** -
* **Remote** -
* **Repository** -


_Citations_
* https://devmountain.com/blog/what-is-github-and-how-do-you-use-it/
* https://www.jetbrains.com/help/webstorm/installation-guide.html
* https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html#ws_getting_started_find_your_way_through_find_symbol_by_name
