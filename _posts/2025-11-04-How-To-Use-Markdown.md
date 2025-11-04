---
title: "How To Use Markdown"
categories:
  - Tutorials
  - Blogs
tags:
  - markdown
  - gitHub
  - pages
  
---


This is just simple text 



**this text is bold**

 *this is text that italics now*

__This is text is bold__

_this is text works as well to make italics_

**_this text is bold as underscored_**

this is ~~strikethrough~~



# Heading 1

## Heading 2

### Heading 3

###### Heading 6




>This is first example

>>This is the second example

>>>This is the third example

This is how I show an image



Image Methods

**File names are case sensitive!!**


Good Practice: use lowercase and hyphens


Simplest Method

![PCB Image](/assets/images/PCB1.jpg)


![PCB Image]({{ "/assets/images/PCB1.jpg" | relative_url }})

This is best practice for Jekyll because it automatically adjusts the path if your site is in a subdirectory (like `username.github.io/project-name`).




Second method more html tag

<img src="/assets/images/PCB1.jpg" alt="PCB Image">


This method allow use to set dimensions

<img src="/assets/images/PCB1.jpg" alt="PCB Image" width="500">



How to create links

You can see the live project [here](https://mrdatlatin.github.io/).


This is my main paragraph. You can see the live project [here][project-link].
I can even talk about the [project-link] again, and it will just work.

... (all your other content) ...

[project-link]: https://mrdatlatin.github.io/