---
published: true
layout: post
title: Posting on CaracolDSA.io
---
## Posting articles

The whole site is hosted in [github.com](notion://www.notion.so/github.com) as a repo (repository). This allows us to modify it using different tools.

[:Git](#whatisgit) repos can be cloned to a local computer. Any changed made, like adding a new article, can be "pushed" or uploaded to the main repo hosted in [github.com](http://github.com/). Any time this happens, the sitet gets automatically rebuilt and published (takes about 30-60 seconds).

## Working with the site locally

[:Git](notion://www.notion.so/How-to-post-articles-4ba68e7f69894dcdab40b4ddaf7d756b#whatisgit) repos can be cloned to a local computer using [github desktop](https://desktop.github.com/). Here you can access and change the files relevant to the style’s style, or you can simply add a new blog article to the “_posts” folder (as a markdown file). 

Any changes you make can be "pushed" or uploaded to the main repo hosted in [github.com](http://github.com/). Any time this happens, the site gets automatically rebuilt and published (takes about 30-60 seconds). If you added a new article to the _posts folder, it would automatically appear on the home page, on the top of the recent articles list. 

![github desktop example]({{site.baseurl}}/assets/media/githubdesktop.png)

![folders example]({{site.baseurl}}/assets/media/githubfolders.png)

## Prose.io

To avoid any tech headaches, the best tool for super straightforward content and post management i’ve found so far is [Prose.io](http://Prose.io). It’s simple and it mirrors the folder structure of the site. Here’s a quick 1-2-3 on how to use it:

1. Go to [github.com](http://github.com) and log into the DegrowDSA account.
2. Go to [Prose.](http://Prose.IO)io and give it access to your github account. Once you’re connected, you get this interface. If you navigate to _posts, you’ll see all currently published posts. From here, you can click on “new file” to start a new post. 

![prose main]({{site.baseurl}}/assets/media/prose1.png)

![prose posts]({{site.baseurl}}/assets/media/prose2.png)

1. Here’s how the editor looks. At this point you can start typing, or you could instead use another edito ([Notion.so](http://Notion.so), google docs, word, etc) and then just copy paste your text here. The text appears in markdown format. if you’ve used wordpress before, you might be familiar with it. [:You just need to make sure things are formatted in the right way - links, images, headings etc.](#markdown) - 
    
    (When you copy-paste from Notion.so, the “rich text” gets automatically formatted to markdown. It might work with other tools. your milage may vary)
    

![prose text editor]({{site.baseurl}}/assets/media/prose3.png)

## Nutshell

A great “plugin” i added to the website is [:nutshell](https://ncase.me/nutshell/#WhatIsNutshell). It allows you to nest short explanations on the  site, as you might have just tried. [Check out the site](https://ncase.me/nutshell) to learn more about it and how to use it. (Nicki Case, the tool’s creator, is the best)

![Nutshell]({{site.baseurl}}/assets/media/nutshell1.png)

## Limitations

Previewing an article before posting can be tricky. I’m still figuring out how to make it easier. For now, the best bet is to either use the [Prose.io](http://Prose.io/s) text editor’s preview button, or if you use a lot of nutshells, the [nutshell text editor](https://ncase.me/nutshell/try/). Worst case, just publish, wait 30-60 secs, and refresh the site.

For this reason, changing the look of the website is also difficult. Modifying jekyll themes means editing code. Changing the fonts is easy enough - just find and replace font names in the .CSS files. Anything more substantial, however, has a bit of a learning curve. 

## Themes

The Jekyll community has many themes that can be swapped to with little effort. I think a theme that has thumbnails next to the posts is the next goal.  Here's some I got my eye on.
- [Alembic](https://jekyllthemes.io/theme/alembic)
- [Cool gallery theme](https://jekyllthemes.dev/maxima-minimal-blog-and-magazine-jekyll-theme/)
- 

## Why this instead of Wordpress?

1. Free
2. Lightweight - follows some of those sustainable web principles
3. Easy to back up
4. [More detailed reasons here.](https://www.sitepoint.com/wordpress-vs-jekyll-might-want-make-switch/)

## :x whatisgit

Git is a distributed version control system that is used for software development and other version control tasks. It was created by Linus Torvalds in 2005. The name "git" is a British slang that means "unpleasant person". Torvalds named the software git as a joke, because he wanted a fast and efficient system, and also because he wanted to name it after himself. ---chatGPT

## :x markdown

Here’s some quick tips that would look like: [https://chesterhow.github.io/tale/2017-03-16/example-content](https://chesterhow.github.io/tale/2017-03-16/example-content)

Here’s a better and more interactive example: [https://ncase.me/nutshell/try/](https://ncase.me/nutshell/try/)
