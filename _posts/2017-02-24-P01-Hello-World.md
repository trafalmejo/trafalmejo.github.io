---
layout: post
title: "Day 01 - Shall we be friends?"
date: 2017-02-24
categories:
  - Personal
description:
image: http://jacobsalzberg.github.io/db/static/path_2000.jpg
image-sm: http://jacobsalzberg.github.io/db/static/path_500.jpg
---


# "Hello, world."<br>
---
###  >> SAO PAULO, FEB. 24th 2017 <<
---
<br><br>

### Why are we here?<br><br>
<div align="justify">
I'll keep this updated for the sake of my mental health. Also, it's a decent tool to keep track of my skills development and general life hacks or just random rant. Most developers have a blog so.. why the hell can't I have one too? I feel like I'm talking to myself, but venting out definitely helps. </div>
<br><br>

#### My first blog: About my day<br><br>
<div align="justify">
I took most of the day off to find out how to get this <i>stupid</i> blog rolling (hello there, let's try to be friends, Mr. CL4PTR4P). In order to do so, as I found a great Jekyll theme, I had to setup linux on my laptop as it's required for Jekyll. So, in order to get the blog working, I had to work on some new skills and try to "unzip" some that were hiding somewhere in my brain.
</div>
 
<figure>
  <img src="https://m.popkey.co/530e0a/XRjLe.gif"/>
  <figcaption>This is how you are seen, Mr. Blog. I hope you enjoy really steep stairs (Borderlands II joke).</figcaption>
</figure>




#### Skill Improvements:<br><br>

* Basic **rewind on Linux** - I decided to install mint 18.1 with cinnamon. I had some experience but I had to get used to the terminal again;
* **Git** usage on bash (mint's gnome based terminal)
* **Jekyll + Bundler** general usage;
* Adding **Gem-Based themes**;
* **Markdown** (.md) synax - it's ultra easy, it's the synax im using to write this post with. It pretty much converts given symbols into html, making it ultra readable;
<div align="justify">
It was a pretty rough ride as I had a lot of issues with gems, mostly related to bad documentation on the theme's end and I had zero previous experience with this. I ended up fixing my problems by using <b>sudo bundle update</b> after cloning the theme's source repo. It literally took me about 4 hours of tweaking and face-smashing the terminal to get this ready, as the general fix-suggestions made no sense.
</div>
<br>But oh well, at last, the blog is running <i>silky smooth</i>. After getting the theme all sorted and github pages ready, here's what I needed to get a build going from linux:

1. Fully edit the post on W10 using Haroopad or atom (it's faster, better keyboard than my laptop);
2. Manually upload the post to github it's faster than using git bash also the images in the static folder;
3. On linux (given you're already on the correct brach, which should be **gh-pages**):
  * **sudo git status** - check if the files were upload properly
  * **sudo git pull**   - clones the changes the local folder
  * **sudo bundle exec jekyll build**  - builds the blog ![Alt](http://jacobsalzberg.github.io/db/static/bexec.png "Hello, terminal!")
  * **sudo git add .** - adds all .html files and other files that were generated
  * **sudo git commit -m "random commit message"** - commits the changes
  * **sudo git push -u origin gh-pages** - pushes them to github
<div align="justify">
Alternativelly, I can just get on github on W10 (seems like I'll be doing this as it's the fastest way), go to my <b>gh-pages</b> branch of my repository, go to the `/_posts/` folder and just create a MARKDOWN file inside of it with my post.
And that's it, github and jekyll handles the rest. Blog is running really fine. Worth the effort, <i>I guess</i>. <br><br>
</div>

### Lessons Learned<br><br>
<div align="justify">
I really need to work on my multi-tasking skills. I "tunnel" (short of "tunnel vision": <i>[informal] the tendency to focus exclusively on a single or limited goal or point of view</i>) too much if there's an issue - if I can't get it solved, I keep trying over and over and over, even if I should be doing something else. This is (somewhat) fine, but not if I'm not moving on the direction of fixing the given issue.
</div>
<br><br>
### Blog plans<br><br>
As for now, I'll start with two blog categories:
* Personal, for my personal updates (yes, as if it was impossible to guess what it was about with such a creative name) and;
* DevBlog, for game-specific updates;

<br>
Let's see how it goes. Just to make this pretty, I'll add a quote:

<blockquote>"Life is short and we have never too much time for gladdening the hearts of those who are travelling the dark journey with us. Oh be swift to love, make haste to be kind."  
<cite>Henri Frederic Amiel</cite></blockquote>

This will be a really tough ride. As hard as it will be, I'll do my best and be kind to those around me. 
Thanks for your time.

***
***
### About the header's painting 

<figure>
  <img src="http://jacobsalzberg.github.io/db/static/path_2000.jpg" />
  <figcaption>Painting by k04sk:  <a href="http://k04sk.deviantart.com/art/Path-333698884" title="Deviant"> [DA]</a> </figcaption>
</figure>

Judging by the angle, this great painting is actually really interesting. At first, what gives the impression of just being a perspective mistake (indeed it is really an illustration mistake, but that's not the relevant point here), is in fact what gives the greatness to this piece of art. The steps do not get narrower across the stairs - they do, however, keep the same width, no matter how many of them one has actually climbed. The same can be said about their height - they all seem to be the same.

Thinking about simple optics, the steps are *de facto* getting wider and higher. We can think about life and what comes across our path in the same way. Seems like a really daunting and steep path at first.. and it might actually be so. Or it might just be a perspective mistake. This is a really deep composition.


