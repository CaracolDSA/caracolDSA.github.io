---
layout: post
title: "Example Content"
author: "Lalo et al"
tags: Example
excerpt_separator: <!--more-->
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas tincidunt ornare nibh, non elementum augue tempus eget. Pellentesque tempus scelerisque iaculis.<!--more--> Nullam interdum ultricies nibh quis sollicitudin. Donec ornare fermentum facilisis. Ut at sem ac sem imperdiet varius a eget tortor. Nam eu augue eget orci semper maximus in eget augue. Mauris ornare, nisl ut suscipit consectetur, mi quam interdum tellus, at rutrum quam eros ultrices mi.

# Headers
{% highlight markdown %}
# H1
## H2
### H3
#### H4
##### H5
###### H6
{% endhighlight %}

# H1
## H2
### H3
#### H4
##### H5
###### H6

# Text formatting
{% highlight markdown %}
- **Bold**
- _Italics_
- ~~Strikethrough~~
- <ins>Underline</ins>
- <sup>Superscript</sup>
- <sub>Subscript</sub>
- Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr>
- Citation: <cite>&mdash; Chester How</cite>
{% endhighlight %}

- **Bold**
- _Italics_
- ~~Strikethrough~~
- <ins>Underline</ins>
- <sup>Superscript</sup>
- <sub>Subscript</sub>
- Abbreviation: <abbr title="HyperText Markup Language">HTML</abbr>
- Citation: <cite>&mdash; Chester How</cite>

# Lists
{% highlight markdown %}
1. Ordered list item 1
2. Ordered list item 2
3. Ordered list item 3

* Unordered list item 1
* Unordered list item 2
* Unordered list item 3
{% endhighlight %}

1. Ordered list item 1
2. Ordered list item 2
3. Ordered list item 3

* Unordered list item 1
* Unordered list item 2
* Unordered list item 3

# Links
{% highlight markdown %}
Check out tale on [GitHub](https://github.com/chesterhow/tale).
{% endhighlight %}

Check out tale on [GitHub](https://github.com/chesterhow/tale).

# Images
{% highlight markdown %}
![Placeholder image](https://placehold.it/800x400 "Placeholder image")

![Image with caption](https://placehold.it/700x400 "Image with caption")
_This is an image with a caption_
{% endhighlight %}

![Placeholder image](https://placehold.it/800x400 "Placeholder image")

![Image with caption](https://placehold.it/700x400 "Image with caption")
_This is an image with a caption_

# Code and Syntax Highlighting
Use back-ticks for `inline code`. Multi-line code snippets are supported too through Pygments.

{% highlight js %}
// Sample javascript code
var s = "JavaScript syntax highlighting";
alert(s);
{% endhighlight %}

{% highlight python %}
# Sample python code
s = "Python syntax highlighting"
print s
{% endhighlight %}

Adding `linenos` to the highlight tag enables line numbers.

{% highlight js  linenos %}
// Sample javascript code
var s = "JavaScript syntax highlighting";
alert(s);
{% endhighlight %}

# Blockquotes
{% highlight markdown %}
> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

{% endhighlight %}

> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

# Horizontal Rule & Line Break
{% highlight markdown %}
Use `<hr>` for horizontal rules

<hr>

and `<br>` for line breaks.

<br>
{% endhighlight %}

Use `<hr>` for horizontal rules

<hr>

and `<br>` for line breaks.

<br>

#USING NUTSHELL

## To write a section,

just use headings & paragraphs like this! Then...

## To embed a section,

just make a link with :colon at the front... [:LIKE THIS](#ToWriteASection)!

## Details about linking to stuff

**To link to a section on the same page**, use a # followed by the text of the section's heading – capitalization, spaces, and punctuation don't matter.

[:This example](#ToEmbedASection) links to `#ToEmbedASection`

**To link to a section from a different page**, link to the URL, followed by # and section heading:

[:This example](https://ncase.me/faq/#GoodMentalHealth) links to `https://ncase.me/faq/#GoodMentalHealth`

**If you link to a page without a #SectionHeading**, it'll embed the *whole* article.

[:This example](https://blog.ncase.me/parable-of-the-hill-climber/) links to `https://blog.ncase.me/parable-of-the-hill-climber/`

**Three notes on embedding from other pages:**

1) Not sure if you're doing it right? Test your link in this demo page! (Remember the :colon in the link text, and the # for the section!)

2) Only embed from sites you trust! They can change their content at any time (but that's problem for regular links, too). You can mirror/copy the site to be extra safe.

3) The other site must either also have Nutshell installed, or [:CORS](../#cors) enabled. If you don't know if the other site has Nutshell/CORS, test out linking to it in this demo page.

## Other Fun Stuff

You want to embed an explanation, but no-one's written it yet & you can't be bothered to either? **Get the intro from a Wikipedia article** by linking to it!

[:Catgirl on English Wikipedia](https://en.wikipedia.org/wiki/Catgirl) links to `https://en.wikipedia.org/wiki/Catgirl)`

[:Baguette on French Wikipedia](https://fr.wikipedia.org/wiki/Baguette_(pain)) links to `https://fr.wikipedia.org/wiki/Baguette_(pain)`

[:Universe on Simple Wikipedia](https://simple.wikipedia.org/wiki/Universe) links to `https://simple.wikipedia.org/wiki/Universe`

**You can also link to YouTube videos so they can expand in-place.** You can even specify a specific starting time – on a YouTube page, click 'Share' then 'Start at [time]'.

[:Knife-Wielding Tentacle, starting at 0:36](https://youtu.be/pQ2dI_B_Ycg?t=36) links to `https://youtu.be/pQ2dI_B_Ycg?t=36`

For more advanced features (like how to make a section hidden by default, get sections by text-search instead of headings, add words before/after an embedded snippet, etc...) check out [the documentation!](https://github.com/ncase/nutshell#advanced-features--options)


_The end_
