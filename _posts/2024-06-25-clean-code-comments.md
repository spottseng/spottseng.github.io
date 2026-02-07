---
layout: post
title: Meaningful Names, Functions, and Comments
subtitle: Reading the first few chapters of Clean Code by Robert Martin
cover-img: /assets/img/cloudy_lake.jpg
thumbnail-img: /assets/img/cloudy_lake.jpg
share-img: /assets/img/cloudy_lake.jpg
tags: [tech, computer_science, books] 
---

Our broader engineering team recently started reading [Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) by Robert Martin, and while some of his opinions seems to be strongly contested within the software engineering world, he is still seen as a thought-leader for writing good software and following reasonable practices. Two of the chapters that stood out to me the most so far were the chapters on Meaningful Names, Functions, and Comments. I took the ideas he lays out in these chapters and applied them to a personal project I'm working on: The [Hinge Data Analysis](https://github.com/spottseng/hinge-data-analysis) project.

Right off the bat one of the first things I noticed was that my lazy and somewhat vague naming of functions and variables made it difficult to revisit parts of the code I hadn't touched in a while. It was really hard to re-read and piece together what was happening, and it made it even more difficult trying to do that while weeding through out of date comments. I realized at this point most of the comments I left were to compensate for poor naming conventions, or to provide visual breaks and explanations for functions that were way too long. Robert Martin talks about how a function should have one purpose, and although there are always exceptions, this is a best practice that I try to follow. Breaking out different aspects of a large function into independent methods helps the readability tremendously, and it also tends to eliminate the need for comments. Once I put more effort into thoughtful naming conventions, it became a whole new project.

Robert Martin's philosophy is to use comments only when necessary when there is something unexpected or unavoidably complicated in the code. This used to be something I disagreed with, but now I see superfluous comments as distracting and a major hazard to maintain. It turns out when things are named articulately and broken into their respective functions, the need for tons of comments goes away. 