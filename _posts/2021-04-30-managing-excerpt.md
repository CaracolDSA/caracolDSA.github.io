---
layout: post
title: "Managing Excerpts and stickies"
author: "Chester"
tags: Tale
excerpt_separator: <!--more-->
---

You can customise the excerpt (the text displayed below each post on the homepage) using the `excerpt-separator`.<!--more--> Here's how you can do so!

## Steps

1. Add `excerpt_separator: <!--more-->` to the frontmatter of your blog post.

2. Insert this `<!--more-->` at where you would like the excerpt to cut off in your blog post.

### Note

This follows [Jekyll's recommended way of managing excerpts](https://jekyllrb.com/docs/posts/#post-excerpts).

## Example

See [this post](https://github.com/chesterhow/tale/blob/master/_posts/2021-04-30-managing-excerpt.md) or the ["Introducing Tale" post](https://github.com/chesterhow/tale/blob/master/_posts/2017-03-29-introducing-tale.md).


# Stickies

Sticky, or pinned, posts are featured on the top of every page. Tale provides some flexibility when it comes to this feature.<!--more--> There is no limit on the number of sticky posts you can have. Although do note that each page will show all your sticky posts + the paginated posts. So if you have 4 sticky posts and 5 posts per page, each page can display up to 9 posts.

## Making a post "sticky"

Add `sticky: true` to the frontmatter of your blog post.

### Exclude sticky post from paginated posts

By default, sticky posts are still included in the paginated posts. To exclude a sticky post from paginated posts, add `hidden: true` to the frontmatter of that blog post.

## Example

See the ["Introducing Tale" post](https://github.com/chesterhow/tale/blob/master/_posts/2017-03-29-introducing-tale.md).