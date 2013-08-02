---
title:  "My first blog"
layout: post
category : lessons
tagline: "For my Gico"
tags : [intro, beginner, jekyll, Gico]
---

{% include JB/setup %}

This essay talks about my first touch into git.
## Overview 

### Git and Github

I finally know that Git and Github are different. The former is designed for version management. And Github is the server to manage the repos. Git is distributed. So you can not only use Github to manage your repo. 

### How to push your repo

Afer you create a new repo on the Github, during the development process, you may push your repo many times, so you must familiar with the following steps:

	git add . //let the server know your changes
    git status //show the files and the changes you have made
    git commit -m "log" //the content between the quotation marks should be replace by your summary to your changes made this time
	git push //now you can push your file 

There must be some preparation for you to use Git and Github. You must install some softwares, you can find how by Google.


## Jekyll

After [installing jekyll](/index.html#start-now) you'll need to format your website directory in a way jekyll expects.
Jekyll-bootstrap conveniently provides the base directory format.

### What does Jekyll Do?
All I know and all I have to know by now is that it can help me make the writing  process easier. 

### Jekyll is Not Blogging Software

**Jekyll is a parsing engine.**

Jekyll does not come with any content nor does it have any templates or design elements.
This is a common source of confusion when getting started.
Jekyll does not come with anything you actually use or see on your website - you have to make it.

### The Jekyll Application Base Format

Jekyll expects your website directory to be laid out like so:

    .
    |-- _config.yml
    |-- _includes
    |-- _layouts
    |   |-- default.html
    |   |-- post.html
    |-- _posts
    |   |-- 2011-10-25-open-source-is-good.markdown
    |   |-- 2011-04-26-hello-world.markdown
    |-- _site
    |-- index.html
    |-- assets
        |-- css
            |-- style.css
        |-- javascripts


- **\_config.yml**  
	Stores configuration data.

- **\_includes**  
	This folder is for partial views.

- **\_layouts**   
	This folder is for the main templates your content will be inserted into.
	You can have different layouts for different pages or page sections.

- **\_posts**  
	This folder contains your dynamic content/posts.
	the naming format is required to be `@YEAR-MONTH-DATE-title.MARKUP@`.

- **\_site**  
	This is where the generated site will be placed once Jekyll is done transforming it. 

- **assets**  
	This folder is not part of the standard jekyll structure.
	The assets folder represents _any generic_ folder you happen to create in your root directory.
	Directories and files not properly formatted for jekyll will be left untouched for you to serve normally.

(read more: <https://github.com/mojombo/jekyll/wiki/Usage>)


## Gico 

Gico is a repo on my Github. I will use it in my blog. So the other people can leave a comment on my blog. Gico use the issue function which has provided by Github. In this blog, I will try it.

