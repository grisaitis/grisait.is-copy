---
layout: post
title: Online Markdown Editors and GitHub Pages
---

 Online Markdown Editors and GitHub Pages

When I started blogging with Jekyll and GitHub Pages, I thought the best approach to writing and drafting posts was to use a markdown editor. My thought process went:
1. Jekyll posts have to be markdown-formatted
3. Lots of people use markdown editors, it seems
4. Many editors offer GitHub integration, with Pages sites in mind

Basically, I'm not fluent in markdown syntax -- the language for formatting these documents with headers, sections, etc. -- and neither do I want to be. And I'd also like to avoid making git commits, managing folders with drafts, and other technical things. I just want to write, which is enough work as it is. 

Here's what I'd like in an editor:
- A Google Docs-like interface
	- Offline editing
	- A good mobile app (or mobile-responsive site)
	- Autosave (when I refresh the page, I should not lose my work)
- Integration with GitHub
- A LaTeX formula editor or syntax assistant

In this post I explore some options, but be warned: **there doesn't seem to be a great markdown editor out there** with the features I think are crucial. The most popular free editors, after to some googling, seem to be prose.io, stackedit.io, and dillinger.io. (Please comment below if you think I'm missing a big one.) I try out the first two, and also a Google Docs plugin for Pages that looked promising but... Well, you'll see. :)

#### Gabriel: A Google Docs Extension for GitHub Pages
My rating: **0 / 5**

Someone actually made a Google Docs plug-in for Pages! ... But I'm not sure it even works. The plug-in, called [Gabriel](https://educ.io/extensions/gabriel), converts docs to markdown and commits them to a Pages repo. But the project code is [unchanged since 2015](https://github.com/thiscouldbejd/Gabriel) and reviews are unenthusiastic on the Chrome Store ([3 stars, 28 reviews](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff)). Nice idea, but not a reliable solution.


#### Prose.io

My rating: **3 / 5** 

Prose.io is a pretty good editor. It's a clean, minimalist app, which summarizes its best and worst aspects. The site is a breeze to use, with no clutter, but in practice prose.io feels incomplete and feature poor. It's basically like editing markdown on github.com, but with a nicer editor and more syncing options. (Actually, the editor might be the same... the [atom](atom.io) editor, open sourced by GitHub.)

A few more critiques...
- No keyboard shortcuts
- No instant preview
- The text editor only takes up 2/3 of the screen (why??)
- Can't move files, e.g. from `_drafts` to `_posts` to publish an article

### StackEdit

My rating: **4 / 5** 

This is the best editor I've tried so far, but it still leaves some things to be desired for this demanding user. 

The interface strikes a great balance between simplicity and displaying useful functionality while editing. The app has two partitions: an editor on the left for writing markdown, and a viewer on the right with instantly rendered text. Neither side feels cramped. StackEdit has most keyboard shortcuts, too, like tab for indentation, but not Cmd + K, oddly, for creating a link. It also feels old (circa 2014?) and there's no mobile app. And anyway, should a text editor get credit for implementing tab indentation in 2019? I'm probably being generous. (Prose.io lowered my standards, I think.)

### Closing thoughts

There are plenty of markdown editors out there, but, honestly, they all kind of suck in some very important way. **Google Docs is still the best text editor.** Sure, it lacks GitHub integration and native support for markdown, but no markdown editor will surpass Google Docs in terms of the writing interface, mobile support, offline editing, collaboration, and everything else that make it indispensable and productive.

Put another way, integration with GitHub is not the most important feature in a markdown editor, and **a markdown editor is not the best solution for managing a Jekyll Pages site**. Would I like a markdown editor to have both GitHub integration and fantastic text editing abilities? Yes, but such an app doesn't exist, at least not to my knowledge.

The best approach when blogging with Jekyll and Pages, then, is probably something like:

1. Draft articles in Google Docs
2. Use a markdown editor, briefly, to convert the document to markdown
3. Publish the article in one of two ways:
	- Manually in GitHub
	- Or via the editor's Pages integration


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAzMjMzNzMxNywtOTA1NTkwNDE5XX0=
-->