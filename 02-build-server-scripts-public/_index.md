---
title: "Build Server Scripts (Public Web Site)"
date: 2023-02-16T9:53:00-04:00
tags: [Public, Build Server, Hugo, GitHub, Scripts, Bash]
type: "book"
---
What is fun?  Authoring a web site.  What is dramatically less fun?  Constantly building the site manually.  Want to change that?

<!--more-->

Manually building the web sites repeatedly get old quick.  Like really, really quick.  The following process will help you setup various `bash` scripts to automate the process of downloaded the web site content from [GitHub](https://github.com/) and the subsequent building of the [Hugo](https://gohugo.io/) output.

*Note: This guide assumes that all the repositories being used are configured to be public.  If even one of them is private, refer to the project for build server scripts (private web sites).*