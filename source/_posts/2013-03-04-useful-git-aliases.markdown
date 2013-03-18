---
layout: post
title: "Useful Git aliases"
date: 2013-03-04 20:36
comments: true
categories: [Git, Version Control]
---

{% img /images/Git-Logo-2Color.png 300 Git Logo %}

These are 3 aliases that i find myself using all the time, since they are used a lot they tend to shorten my workflow a little bit. I'm using the jQuery repo for examples.

### Short status
{% codeblock %}
git config --global alias.s "status -s"
{% endcodeblock %}

{% img center /images/git_short.png git s preview %}

Shortens git status, making it more readable and useful for a quick overview of staged and unstaged changes.

### One Line Log

{% codeblock %}
git config --global alias.ol "log --oneline"
{% endcodeblock %}

{% img center /images/git_ol.png git ol preview %}

Provides a quick overview of the recently done commits without the author and date. Good for finding a commit hash for a quick checkout.

### Quick branch and checkout

{% codeblock %}
git config --global alias.b "checkout -b"
{% endcodeblock %}

{% img center /images/git_branch.png git b preview %}

Creates a new branch and instantly switches the newly created branch.