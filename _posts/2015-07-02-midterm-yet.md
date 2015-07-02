---
layout: article
title: "Midterm already?"
date: 2015-02-07
categories: gsoc
excerpt: "My Google Summer of Code post for midterm."
tags: [gsoc, fossasia, midterm, steam]
ads: true
image:
  feature: gsoc2015.png
  teaser: joint_gsoc_fossasia.jpg
---
{% include toc.html %}

First of all, I really thank Google for organizing such an event for students in the summer and I am fortunate to be a part of such a program. I would also like to thank FOSSASIA for accepting my proposal for the project and for providing me with the experience of working with them.

_**When you see your name on the list**_

Name on the list? Google’s server being stacked up with lots and lots of request, Students impatiently clicking the refresh button to see whether their names are present in the list, A lot of students, A lot of projects, and suddenly, that one refresh, when the list loads with the projects matching the student names. (CTRL+F)”Trilok Tourani” and there it was,

- Organization : FOSSASIA
- Project : Improve the command line tools of the sTeam collaboration platform
- Student : Trilok Tourani
- Mentors : Martin Bahr(Working mentor) , Chris Angelico, Aruna Herath, Markus(Backup mentors)
- Status : Accepted

Dumbstruck for a minute, but when it hit me, that I got selected, the happiness was beyond what I had expected. I went on the IRC and thanked my mentors. All I knew was I had a project in hand and a long way ahead to perform beyond their expectations.

* * *

_**About the project**_

What is sTeam?

sTeam is a collaboration platform which helps people to share their documents, chat with them, have a look at their virtual workarea, and ease the sharing/developing in big groups. You can also look at the current development on the sTeam web interface [here](http://steam-web.azurewebsites.net/). It is still in the development phase, so please feel free to provide us with any ideas to improve. To know more about sTeam, please visit [societyserver](http://societyserver.org/).

sTeam is completely built on pike programming language. To know more about pike programming, please visit http://pike.lysator.liu.se/. If you already know about pike, and are good at it, please visit Fossasia’s IRC channel #fossasia and ask for tasks/bugs on this project to solve right away. If you are looking for something other than sTeam, FOSSASIA has a wide range of projects in various fields, and also welcomes any new project ideas.

* * *

_**My part of the project**_

I would like people to know the kind of work that I am doing currently for sTeam and show them how interesting it is to develop for it.

My project is to develop the command line tools to ease the work for the developers, and people who choose to work with command line, over a web interface.

These tools include,

- Exporting your documents to your Github repository with just a command.
- Importing document from Github right into sTeam for people to see.
- A easy to use debug client that helps you while developing for this platform, or to see the various documents/containers you have in which room, move them, copy them, use them, all with commands similar to the Linux command line.
- A way of to edit your documents directly with command line editors, without having to go to the web, type in the url, clicking on a document, and then finally editing it.
- Chat with your friends/group members over the IRC.
- and more being added to the list….(Please contact us if you have any)

These tools are already built up, but with more development, they will be very efficient and easy to use commands which a normal user can type in and get things done, and this is where my part comes in.

For some of these tools, which are already built, some development is needed. While some other tools, I have to develop by myself and enhance the command line usage for sTeam.

These are few of the commands with their screenshots to help you understand exactly what these tools are meant for,

The sTeam debug client,

![debug.pike]({{ site.url }}/images/debug1.png)

The editing documents client,

![edit.pike-usage]({{ site.url }}/images/edit2.png)

and edit the document in a simple command-line editor (used vim here),

![edit.pike-interface]({{ site.url }}/images/edit1.png)

Exporting documents from sTeam to git (version-wise)

![export-to-git.pike]({{ site.url }}/images/debug1.png)

Importing documents to sTeam from git (version-wise)

![import-from-git]({{ site.url }}/images/import1.png)

If you really like what I am doing, or are interested in developing for sTeam, please join our IRC channel #fossasia or join fossasia@googlegroups.com .

If you are looking for some other project, FOSSASIA has a lot of projects to be worked on. Please visit [FOSSASIA](http://fossasia.org/) for more info.
