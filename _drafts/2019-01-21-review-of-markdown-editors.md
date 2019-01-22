## Online Markdown Editors and GitHub Pages

When I started blogging with Jekyll and GitHub Pages, I thought the best approach to writing and drafting posts was to use a markdown editor. My thought process went:
1. Jekyll posts have to be markdown-formatted
3. Lots of people use markdown editors, it seems
4. Many editors offer GitHub integration, with Pages sites in mind

Basically, I'm not fluent in markdown syntax -- the language for formatting these documents with headers, sections, etc. -- and neither do I want to be. And I'd also like to avoid making git commits, managing folders with drafts, and other technical things. I just want to write, which is enough work as it is. 

Here's what I' looking for in an editor:
- Offline support
- A mobile app, or a good mobile browser design
- Integrations with Google Docs and GitHub
	- I'd like to edit articles via Google Docs, especially if offline and mobile support is scant.
- Caching drafts
	- When I refresh the page, I should not lose my work
- A LaTeX editor, formula builder, or something to help with LaTeX syntax

So what's the best editor? Does a good one even exist? What features are most important for a Pages blog? An ideal editor would be something like Google Docs with two additions: (1) the ability to sync with GitHub and (2) a LaTeX editor for math expressions. Does something like this exist? No.



I haven't found anything that checks all my boxes, but I've tried a few. The most popular free editors, after to some googling, seem to be prose.io, stackedit.io, and dillinger.io. (Please comment below if you think I'm missing a big one.)

#### Gabriel: An Extension to Google Docs
My rating: **0 / 5**

Someone actually made a Google Docs plug-in for Pages... but I'm not sure it even works. The plug-in, called [Gabriel](https://educ.io/extensions/gabriel), converts docs to markdown and commits them to a Pages repo. But the project code is [unchanged since 2015](https://github.com/thiscouldbejd/Gabriel) and reviews are unenthusiastic on the Chrome Store ([3 stars, 28 reviews](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff)). 


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

This is the best editor I've tried so far, but it still leaves some things to be desired for this picky writer. 

The interface strikes a great balance between simplicity and making as many options visible to you for editing. The app is divided in two: the left side is for writing in markdown, and the right side renders the result instantly. Neither side feels cramped. StackEdit also sports most keyboard shortcuts, like tab for indentation. 

On the downside, it feels old (circa 2014?) and has no mobile app. And should a text editor - in 2019 - really get credit for implementing tab indentation?

### Closing thoughts

There are plenty of markdown editors out there, but I don't expect to do all my writing in one. **Google Docs is the best text editor.** No markdown editor will surpass it in terms of interface, mobile support, offline editing, collaboration, and all the other features that make it indispensable and productive.

Put another way, integration with GitHub is actually not the most important feature in a text editor. Would I like a great text editor to have this, in addition to handling markdown for me? Yes, but I'm afraid such an app doesn't exist. Even if an editor has seamless GitHub syncing, it's useless -- to me -- if the writing interface isn't amazing.

The best approach to blogging with Jekyll and Pages, then, is:
1. Draft in Google Docs
2. Use a markdown editor, briefly, to convert the document to markdown
3. Publish the article in one of two ways:
	- Manually in GitHub
	- Or via the editor's Pages integration


<!--stackedit_data:
eyJoaXN0b3J5IjpbMTA0OTg0OTQ0MywyMTE0MzI3MTZdfQ==
-->