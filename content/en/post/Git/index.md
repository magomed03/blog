---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Git"
subtitle: "What is git and what is it eaten with"
summary: "What is git and what is it eaten with"
authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
date: 2022-05-06T18:20:08+03:00
lastmod: 2022-05-06T18:20:08+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## What is Git?

Git has become the world standard for version control. So what is it?

Git is a distributed version control system. This means that the local clone of the project is a full version control repository. Full-featured local repositories make it easier to work offline or in a remote location. Developers commit their work locally, and then synchronize their copy of the repository with the copy on the server. This paradigm differs from centralized version control systems, where clients must synchronize code with the server before creating a new version of the code.

The flexibility and popularity of Git make it a great choice for any team. Many developers and college students are already familiar with using Git. The Git user community has created many resources for training Git developers and developers, which makes it easier to get help if necessary. Almost every development environment has Git support, and Git command-line tools run on every major operating system.

## Git Basics

Every time a job is saved, Git creates a commit. A commit is a snapshot of all files at a given time. If the file has not been changed from one commit to the next, Git uses the previously saved file. This project is different from other systems that store the original version of the file, and at the same time records of the differences are saved.

Commits create links to other commits, forming a timeline of the development history. You can return the code to the previous commit, check how the files changed from one commit to the next, and view information, for example, where and when changes were made. Commits are defined in Git by a unique cryptographic hash of the commit content. Since everything is hashed, it is impossible to make changes, lose information or damage files without detecting them.

## Branches

Each developer saves changes in their own local code repository. As a result, there may be many different changes based on a single commit. Git provides the means to isolate changes and then merge them. Branches, which are lightweight pointers to the tasks being performed, manage this separation. After completing the work created in the branch, this branch can be merged back into the main branch of the team (or trunk).

## Files and Commits

Files in Git are in one of three states: modified, intermediate, or committed. When the file is changed for the first time, the changes exist only in the working directory. They are not yet part of the commit or development history. The developer must place the modified files for inclusion in the commit. The staging area contains all the changes that are included in the next commit. When the developer is satisfied with the intermediate files, they are packaged as a commit with a message describing the changes. This commit will become part of the development history.

Intermediate storage allows developers to choose which file changes should be saved in a commit in order to break large changes into a series of small commits. By reducing the scope of commits, it is easier to view the commit log to find certain changes in files.

## Advantages of Git

### Simultaneous development

Each has its own local copy of the code and can work simultaneously with its own branches. Git works offline, since almost every operation is local.

### Quick Releases

Branches provide flexible and simultaneous development. The main branch contains stable and high-quality code from which it is released. Component branches contain work in progress, which are merged into the main branch after completion. Separating the release branch from the development environment simplifies stable code management and speeds up the delivery of updates.

### Built-in integration

Because of its popularity, Git is integrated into most tools and products. Every major integrated development environment has built-in Git support, and many tools support continuous integration, continuous deployment, automated testing, tracking of work items, metrics, and integration of reporting functions with Git. This integration simplifies the day-to-day workflow.

### Support for trusted communities

Git is open source and has become the de facto standard for version control, so there are not enough funds and resources for workgroups. The amount of community support for Git compared to other version control systems makes it easier to get help when needed.

###Git works with any command

Using Git with the source code management tool allows you to increase the efficiency of the group's work by applying policies that automate processes and improve visibility and traceability of work. The team can match individual tools for versioning, tracking work items, and continuous integration and deployment. In addition, they can choose a solution like GitHub or Azure DevOps that supports all these tasks in one place.

### Pull Requests

Use pull requests to discuss code changes with the team before merging them into the main branch. Discussions in pull requests are valuable for ensuring code quality and increasing knowledge in the group. platforms such as GitHub and Azure DevOps offer ample opportunities for requests to include changes made, when developers can view changes in files, leave comments, check commits, view builds and vote for code approval.

### Branching Policies

Teams can be configured by GitHub and Azure DevOps to enforce consistent workflows and processes in a group. They can set up branch policies to make sure pull requests meet the requirements before completion. Branching policies protect important branches by preventing direct push notifications, requiring reviewers, and ensuring clean builds.

## Conclusion

Now you have figured out the basics of version control, got an idea of Git and found out why software development teams should use this system.