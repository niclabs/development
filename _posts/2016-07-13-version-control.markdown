---
layout: post
title:  "Version Control System"
date:   2016-07-13 10:21:42 -0400
categories: index dev niclabs
---
## What is it

A Version Control System (VCS) is a system that records changes to a file or set of files over time so that you can recall specific versions later. (Yes, kind of having this: *doc1.txt, doc2.txt, docfinal.txt, docfinalfinal.txt*)

## Types of VCS
- **Local VCS**: Using the previous approach is very simple, so it's very common. However is incredibly error prone, you can forget the order and write to the wrong file, overwrite your previous version, etc.

  This is an example of a local VCS, but there is also software with more advanced feature to do version control locally. *(RCS)*

- **Centralized VCS**: Many times people do not write code own their own, so they collaborate with different people. To solve this issue the Centralized VCS were developed. This type of system have a single server that contains all the files and client check out files from there. *(Subversion, CVS, Perforce)*

- **Distributed VCS**: Centralized solutions have an important caveat, there is a single point of failure, if the server goes down during that period nobody can collaborate. Distributed VCS clone a full backup of all the data at each client to solve this problems. *(Git, Mercurial, etc.)*

## Why do we use a VCS

Usually the projects at the lab are developed by a group of people, so collaboration is a requirement. Also, many people is coming aboard every time, so we prefer to use a system where new-(not so new too)user-errors are not so harmful for other developers in the same project. Most of the time projects are released with an open source license to the community, so the use of popular tools makes easy for new users to collaborate or get engadged in the projects. We do use Git as Version Control System and [GitHub][github] as remote server and graphical web interface for managing project and teams.

## Based on

1. [wikipedia](https://en.wikipedia.org/wiki/Version_control)
2. [git-scm.com](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
3. [makeuseof.com](http://www.makeuseof.com/tag/git-version-control-youre-developer/)

[github]: https://www.github.com/niclabs
