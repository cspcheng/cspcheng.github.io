---
title: 'Linux Network Commands'
date: 2014-11-27
collection: programming
category: "linux"
permalink: /posts/2014/11/27/linux/
tags:
  - admin
  - linux
  - network
---

#### 1.List the Open Ports and the Process That Owns Them

So how do you list the network open ports on your Linux server and the process that owns them? The answer is simple. Use the following command (must be run as the root user):


	sudo lsof -i
	sudo netstat -lptu
	sudo netstat -tulpn
	
