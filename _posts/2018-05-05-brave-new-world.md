---
layout: post
title:  "Brand New World"
date:   2018-05-05 08:28:01 -0400
categories: jekyll program
---

This is the 1st post of this blog. Actually, this is my 2nd try to do blog with Jekyll. Only this time, I'm starting from scratch without any theme or plugin at the beginning. Of course, I'll add them piece by piece, just one step at a time. I just want to record how I build this site, so that I won't forget how to do blog with my 3rd try. Let's be realistic, I'm not gonna promise I can keep creating content to keep this blog alive.

What should I post on this blog? Maybe it's easier to keep this blog as a notebook, just to share what I've learnt, or simply someting I feel cool.

Let's get back to the site itself. To create a Jekyll site is simple, if you are familiar with Ruby. It's as simple as
{% highlight bash %}
gem install jekyll bundler
jekyll new my_blog
cd my_blog
bundle exec jekyll serve
{% endhighlight %}
Your site will be right at [https://localhost:4000](https://localhost:4000) waiting for you. For those of you who doesn't know static site generator or Jekyll at all, I think [this youtube playlist][youtube] is a good place to start with. After all, everyone need to go back to the [Jekyll officail site][Jekyll] to check the documents every once in a while.

The last step is to deploy your blog. To deploy the blog on github is a easy and free choice, and that's what I do. Just create a new branch with name gh-pages, and push it to remote repo, then everything is done. There's a more comprehensive [Guide on github][Github] for how to set up your side on github.

That's all for the first post.

[youtube]: https://www.youtube.com/watch?v=T1itpPvFWHI&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB
[Jekyll]: https://jekyllrb.com/
[Github]: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
