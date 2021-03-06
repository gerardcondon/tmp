---
title: "Moving the blog to Octopress"
date: 2012-02-16 20:11
tags: octopress
keywords: blog, Wordpress, Octopress, static
---
I've decided to switch the blog from [Wordpress.com](http://www.wordpress.com) to an [Octopress](http://www.octopress.org) site hosted on [Github Pages](http://pages.github.com). From now on there will be no more new posts on Wordpress. I've also registered the domain [gerardcondon.com](http://www.gerardcondon.com) and will be using this address for the blog in future. 

I have a few reasons for switching

* I found Wordpress.com to be an excellent site in general. When starting off it was very easy to create and get the blog up and running. However you have to use their site to create your posts. Even if you use a text editor you still ultimately have to paste the post into their site, and all subsequent edits have to be done through Wordpress.com. Also the definitive version of the posts are stored in their database. 

    I prefer to write my documents in plain text files using a markup language. Previously I've used [Latex](http://www.latex-project.org/) and more recently I've started using [Markdown](http://daringfireball.net/projects/markdown/). This has a number of advantages, namely the files can be edited in any editor on any platform and they work very well with source control. Also by separating the content from the typesetting phase, I find that you concentrate better on the actual writing. I hate having to wrestle with formatting in Word; I much prefer leaving that to a program. Donald Knuth & Co. have forgotten more about typesetting than I will ever know.

    Wordpress.com doesn't support Markdown so posting involved an extra step of converting the Markdown to HTML. This meant that I had two versions of the blog. One in Markdown on my local machine and another in HTML on Wordpress. For me, it's an axiom that whenever you have two versions of the same data, they will get out of sync. One needs to be the main source. I wanted the local Markdown version to be the canonical version of the site and everything else derived from that.

* I think the default Octopress theme looks really good (I really like the Archive page). I first noticed it on [Matt Gemmell's](http://www.mattgemmell.com) site and was impressed by how it looked. It also looks well on mobile sites. I have full control of the css using Octopress so I can tweak whatever I want. I liked the [Titan](http://theme.wordpress.com/themes/titan/) theme on Wordpress except I hated the crosses using for lists. On Wordpress.com there was no way to change these. However on Octopress I make any kind of style update.

* I realised that I should get my own domain name instead of using the Wordpress.com address. In future if I need to move my site I can just redirect the domain name and any old links will still work. Whereas I will never own or control the gerardcondon.wordpress.com links. It's better to move now, rather than after I create lots of content at a non portable url. Start as you mean to go on.

The posting workflow is much better now. I write my posts in Markdown on the Mac or on iOS via [WriteRoom](http://www.hogbaysoftware.com/products/writeroom). Then I run a command from the terminal to regenerate the site and deploy it to Github. Edits work in the same way. The Markdown files also get committed to Github ensuring that no matter where I move the blog in future I will always have the content in an accessible file format. 

I'll add a few posts in future on how I got Octopress, Github and my domain all set up and working together.
