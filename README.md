# A02

## Git, GitHub, and WebStorm - A Guide
This is an all-in-one guide for dealing with Git, GitHub, and Jetbrains's WebStorm application. A user looking to make their own website in WebStorm using Git and GitHub should start here!

------------

### GitHub
#### Make a GitHub Account
Firstly, we must make a **GitHub** account!
[According to Wikipedia, GitHub is a platform that allows developers to create, store, manage, and share code](https://en.wikipedia.org/wiki/GitHub "According to Wikipedia, GitHub is a platform that allows developers to create, store, manage, and share code"). By using GitHub, you allow fellow developers to see the process you went through when creating this website.
To create an account, head to their [registration page](https://github.com/signup "registration page") and follow the steps provided.

#### Create a remote repository
Now, we must create a **repository**. Head to the navbar at the top, click on your profile picture in the top right, and click on "Your repositories." We're on the verge of creating a **remote** repository which is where our files will be hosted on GitHub.
Click on "New," fill out the information it requests, and make sure to tick the box that asks if you would like a README.md file. We'll edit this file more later.
Ensure that your repository's visibility is set to whatever visibility you would prefer. If you would like for others to see your repository immediately, set it to public. If you would like for others to only see your repository once it's finalized, you can set it to private for now and set it to public later.

------------

### Git
#### Download Git
Now, we must download **Git**. Git is a version control system that tracks changes in files and projects. [According to Wikipedia, it's usually used by software developers that are collaboratively developing source code during software development](https://en.wikipedia.org/wiki/Git "According to Wikipedia, it's usually used by software developers that are collaboratively developing source code during software development"). You can download Git by [heading to their site and clicking on the appropriate download](https://git-scm.com/downloads "heading to their site and clicking on the appropriate download"). Download the standalone installer (or portable version if you prefer) and follow the setup wizard's steps to install Git on your system.

#### Understanding Git - A Crash Course
Git is mostly simple to understand, and once you get the hang of it, you'll be using it with relative ease. For starters, you can use it to **add**, **commit**, and **push** files from a local repository to a remote one on GitHub. This involves adding files to "staging," committing them for delivery to the remote repository, and then pushing them to the remote repository.

As an analogy: Imagine a box. This box is currently empty, but will contain files that are to be delivered to GitHub. We'll call this the "staging" box. To add files to this box, we must use the **add** command. We use "git add" followed by the name or filepath of whatever file(s) we wish to add to put it in the box. Once we've done this with every file we wish to add, we're ready to commit. Committing involves marking the box with a message that states *what* we've added and *why* so that anyone on GitHub can see what we contributed. Finally, pushing is the act of taking the box and delivering it to GitHub.

Likewise, you can **fetch** or **pull** from a remote repository into a local one that you've **cloned**. Just as pushing is equivalent to delivering a box of files to GitHub, pulling is the act of receiving a box of files from GitHub. It's best used to update **branches** that we have to keep our work up to date.

[According to GitHub documentation, branches are parallel versions of repositories used to isolate development work without affecting other branches in the repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches "According to GitHub documentation, branches are parallel versions of repositories used to isolate development work without affecting other branches in the repository"). We can work on one branch and eventually **merge** into a larger branch once we've finalized our work, but be careful! If there's conflicting file changes, that can lead to **merge conflicts** which need to be resolved before any merges can be made!

------------

### WebStorm
#### Download WebStorm
The next step is to download WebStorm. WebStorm is an IDE made for web, JavaScript, and TypeScript development.  To download it, [head to this link](https://www.jetbrains.com/webstorm/ "head to this link").
Ensure that you have the student developer license. In order to use WebStorm or any of Jetbrains's software free of charge (for a limited time), you need to be approved for a student developer license by providing valid documentation of your current enrollment in college.

#### Setting Up
When you've successfully finished setting up the WebStorm installation, you're ready to begin setting up your coding environment! Once you're in the menu, hit **CTRL + ALT + S** to open up the settings menu. This will allow you to make some important changes before you begin your development journey in WebStorm. Head to **Version Control > Git** and under "Path to Git executable," link the path to the Git executable file. Typically, it's under C:\Program Files\Git\bin on Windows, but the file location may vary according to the installation preferences and operating system.
Once it has been located, head to **Appearance & Behavior > System Settings > Passwords** to ensure that the password file is in a preferred file location.

#### Create a local repository
Finally, clone your remote repository as a local repository. You can do this by going to the main menu, selecting **Checkout from Version Control > Git** OR from within WebStorm, **VCS > Checkout from Version Control > Git.**
Once your repository is created, you are free to add, commit, and push any changes you make locally! You are ready to code!

------------

### Glossary
- **Branch** -  Parallel versions of repositories used to isolate development work without affecting other branches in the repository.
- **Clone** - A copy of a repository that exists locally instead of on a server (or the act of making that copy).
- **Commit** -  A revision or change to an individual file or set of files that is usually accompanied by a message to show what has been changed.
- **Fetch** - The act of adding changes from the remote repository to the local working branch without committing them.
- **Git** - An open source program for tracking changes in text files.
- **GitHub** - A platform that allows developers to create, store, manage, and share code, typically used within software development.
- **Merge** - Taking the changes of one branch and applying them in another via an update.
- **Merge Conflict** - A difference that occurs between merged branches. Merge conflicts usually occur as a result of mismatched file changes. These must be resolved before a merge can successfully take place.
- **Push** - The act of sending, or pushing, changes to a remote repository.
- **Pull** - The act of receiving, or pulling, changes from a remote repository. This goes one step beyond fetching and actually merges the changes from remote into local. Pulling helps keep local files up to date.
- **Remote** - The version of a repository that is hosted remotely on a server such as on GitHub.
- **Repository** - It can be analogous to a project's folder where all the project's files are contained and managed. There can be a local repository on one's computer and a remote repository on a server.

------------

### References

https://en.wikipedia.org/wiki/GitHub

https://github.com/

https://en.wikipedia.org/wiki/Git

https://git-scm.com/downloads

https://www.jetbrains.com/webstorm/

https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches

https://docs.github.com/en/get-started/learning-about-github/github-glossary