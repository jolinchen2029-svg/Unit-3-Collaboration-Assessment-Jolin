# Short Response Questions

**1. If you are collaborating with a classmate what is the first thing that each of the team members needs to do? Why is it important to do this step?**

The first thing team members should do is add each other to the repository so you both will bed able to work on codespaces and then merge your work together in the end. It is also to establish a shared goal and agree on how to communicate and divide work. This is important because it creates a clear roadmap for the project, prevents misunderstandings, and ensures everyone is accountable and working together efficiently to achieve the same outcome. 

**2. Why do developers use branches?**

Developers use branches to create isolated workspaces for developing new features, fixing bugs, or experimenting with ideas without disrupting the main codebase. This separation allows for safer, parallel work, improves collaboration, simplifies code review, and keeps the main project stable and clean. 

**3. What is git? What is github? How does git and github work together?**

Git is a distributed version control system. It is a powerful, open-source tool that tracks changes in source code during software development. GitHub is a web-based platform that provides hosting for Git repositories. It builds upon Git's core functionality by adding features for collaboration, project management, and social coding. Git is the underlying version control system, while GitHub is a service that hosts and enhances Git repositories. Developers use Git commands locally on their machines to manage their code, track changes, and create branches.

**4. What is wrong with the following command sequence? What should be the correct command sequence?**
```
git commit -m "saving work"
git add .
git push
```

The error in this command sequence is the order it is typed in. `git add` is supposed to be the first command to add every modified file into your next commit and allow you to add everything all at once. The second command should be `git commit -m "saving work"` which adds a label to your packaged code and be relevant to what you changed in your file. The third command is fine where it is because its supposed to be `git push` which is already prompted.
```
git add .
git commit -m "saving work"
git push
```