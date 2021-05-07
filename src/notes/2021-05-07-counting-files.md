---
title: "File Count"
date: "2021-05-07T10:38:23.200Z"
syndicate: true
tags: 
- Linux
- Ubuntu
---
Recently I was looking for a way of counting files in a directory:

``ls -la | wc -l`` returns a file count and that is how we discovered there were 379k log files in the home directory today (for one of our systems)!