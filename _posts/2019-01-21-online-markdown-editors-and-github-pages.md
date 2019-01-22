---
layout: post
title: Online Markdown Editors and GitHub Pages
---

When I started blogging with Jekyll and GitHub Pages, I thought the best approach to writing and drafting posts was to use a markdown editor. My thought process went:
1. Jekyll posts have to be markdown-formatted
2. Lots of people use markdown editors, it seems
3. Many editors offer GitHub integration, with Pages sites in mind

Basically, I'm not fluent in markdown syntax -- the language for formatting these documents with headers, sections, etc. -- and neither do I want to be. And I'd also like to avoid making git commits, managing folders with drafts, and other technical things. I just want to write, which is enough work as it is. 

Here's what I'd like in an editor:
- A Google Docs-like interface
	- Offline editing
	- A good mobile app (or mobile-responsive site)
	- Autosave (e.g. refreshing the page doesn't lose your work)
- Integration with GitHub
- A LaTeX formula editor or syntax assistant

In this post I explore some options, but be warned: **there doesn't seem to be a great markdown editor out there** with the features I think are crucial. The most popular free editors, after to some googling, seem to be [Prose.io](prose.io), [StackEdit.io](stackedit.io), and [Dillinger.io](dillinger.io). (Please comment below if you think I'm missing a big one.) I tried out the first two, and also a Google Docs plugin for Pages that looked promising but... Well, you'll see. :)

### Prose.io

My rating: **3 / 5** 

Prose.io is a pretty good editor. It's a clean, minimalist app, which summarizes its best and worst aspects. The site is a breeze to use, with no clutter, but in practice prose.io feels incomplete and feature poor. It's basically like editing markdown on github.com, but with a nicer editor and more syncing options. (Actually, the editor might be the same... the [atom](atom.io) editor, open sourced by GitHub.)

Many features are missing from the experience, though. No keyboard shortcuts. No instant preview. It can't move files, which means you can't publish articles by, for example, moving them from `_drafts` to `_posts`.  And inexplicably the text editor uses 2/3 of the screen. The remaining white space stands as a monument, in a way, to the app's unfinished state -- a subtle yet vast reminder of how disappointing the editor is. Or maybe that's just me. :)

### StackEdit

My rating: **4 / 5** 

This was the best editor I tried, but it still left some things to be desired.

The interface strikes a great balance between simplicity and displaying useful functionality while editing. The app has two partitions: an editor on the left for writing markdown and a viewer on the right with instantly rendered text. Neither side feels cramped. StackEdit has most keyboard shortcuts, too, like tab for indentation... but not Cmd + K, oddly, for creating a link. It also feels old (circa 2014?), and there's no mobile app. And besides, should a text editor get credit for implementing tab indentation in 2019? I'm probably being generous. (Prose.io lowered my standards, I think.)

### Gabriel (Google Docs Add-on)
My rating: **? / 5**

This isn't a markdown editor, but rather a Google Docs add-on for Pages. But I'm not sure it even works: the project code is hasn't changed [since 2015](https://github.com/thiscouldbejd/Gabriel) and [reviews are unenthusiastic](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff) on the Chrome Store. . The add-on, [Gabriel](https://educ.io/extensions/gabriel), converts docs to markdown and commits them to a Pages repo. But Nice idea, but probably not a reliable solution.

## Closing thoughts

There are plenty of markdown editors out there, but, honestly, they all kind of suck in some very important way. **Google Docs is still the best text editor.** Sure, it lacks GitHub integration and native support for markdown, but no markdown editor will surpass Google Docs in terms of the writing interface, mobile support, offline editing, collaboration, and everything else that make it indispensable and productive.

Put another way, integration with GitHub is not the most important feature in a markdown editor, and **a markdown editor is not the best solution for managing a Jekyll Pages site**. Would I like a markdown editor to have both GitHub integration and fantastic text editing abilities? Yes, but such an app doesn't exist, at least not to my knowledge.

The best approach when blogging with Jekyll and Pages, then, is probably something like:

1. Draft articles in Google Docs
2. Convert the document to markdown
	- This add-on looks great: [Docs to Markdown](https://chrome.google.com/webstore/detail/docs-to-markdown/igffnbdfnodiaphfmfaiiaegmoljbghf) 
3. Publish the article in one of two ways:
	- Manually in GitHub
	- Or via the editor's Pages integration


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjY0NzQyNTI2LDU1NzQxNjc4OCwxMDMyMz
M3MzE3LC05MDU1OTA0MTldfQ==
-->