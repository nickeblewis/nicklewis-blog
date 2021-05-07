---
title: "Find a file by wildcard"
date: "2021-05-07T10:55:23.200Z"
syndicate: true
tags: 
- Linux
- Ubuntu
---

Let's imagine you've a tonne of log files in a directory that are eating up space, you want to find those that are older than two months and then potentially delete those in order to keep just the recent ones...

``find . -mtime +60 -name "wp-load.*"`` where we needed to list the files starting with a certain name and that are older than 60 days, in other words we only wanted to keep the most recent log files.

To delete these, we would need to add the ``-delete`` flag to this command. Does it work though? is a ``sudo`` necessary?