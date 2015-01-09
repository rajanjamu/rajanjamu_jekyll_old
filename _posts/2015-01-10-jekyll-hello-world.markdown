---
layout: post
title:  "Setting up Jekyll in 5 mins"
date:   2015-01-10 11:52:26
categories: jekyll tutorial
---
Let me walk you through the steps to setup jekyll for you static website. You can also find it on <a href="http://jekyllrb.com/">Jekyll</a> website

<ol>
  <li>Install jekyll on your system
    {% highlight ruby %}
    $ gem install jekyll
    {% endhighlight %}</li>
  <li>Create a repository on your github account - username.github.io</li>
  <li>Open terminal. Move to your workspace folder.</li>
  <li>Create new jekyll application as follows.
    {% highlight ruby %}
    $ jekyll new username.github.io
    {% endhighlight %}
    You should now have a folder called username.github.io in your workspace folder.</li>
  <li>Move to username.github.io on terminal. You can now open text editor you like and explore the world of jekyll</li>
  <li>Commit the changes on github
  {% highlight ruby %}
    $ git init
$ git add .
$ git commit -m "first commit"
$ git remote add origin gihub_url
  {% endhighlight %}</li>
  <li>Time to party</li>


</ul>