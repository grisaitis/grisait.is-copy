## Online Markdown Editors and GitHub Pages

Using a markdown editor is a great way to draft and publish blog posts for a Jekyll + GitHub Pages site. I'm not fluent in markdown syntax -- the language for formatting text in these documents, with headers, sections, and so on -- and neither do I want to be. And beyond markdown I want to avoid technical details like formatting pages, making git commits, managing folders with drafts, etc. 

But what's the best editor, and what features are most relevant for a Pages blog? The most popular free options, according to some googling,  are prose.io, stackedit.io, and dillinger.io. (If I'm missing a big one, please comment below.)

If I could create an ideal workflow out of thin air, I'd add a Google Docs extension that can edit and sync markdown files in my site's GitHub repo. And perhaps also a LaTeX editor for math formulas. 

That said, here are some features I'm looking for
- Draft caching: Will I lose my work if I refresh the browser while drafting a new document?
- Mobile friendliness: Is there an app? A responsive website?
- Offline mode
- Integrations with Google Drive and GitHub
- LaTeX editing: a formula builder or editor to assist with LaTeX syntax
- Text blocks formatted for code, quotes, etc

#### Project Gabriel

It turns out someone did in fact make an interesting Google Docs plugin, but it gets bad reviews and was abandoned in 2015. The plug-in, [Gabriel](https://educ.io/extensions/gabriel), converts docs to markdown and commits them to a Pages repo. Unfortunately the source code is unchanged since 2015 and the product gets unenthusiastic reviews on the Chrome Store ([3 stars, 28 reviews](https://chrome.google.com/webstore/detail/gabriel/okimajjeocnndpifeelaajdebkkbckff)).

#### Prose.io

**3.5 / 5** This oft-mentioned editor is solid but rather spartan. The interface is similar to editing markdown on github.com but with a nicer editor and more syncing options. (Actually, it might use the exact same editor, [atom](atom.io).)

 The good:
- Clean interface

The bad:
- No keyboard shortcuts (e.g. Cmd + K for links)
- No instant preview
- Weird markdown editing behavior
  - E.g, clicking a header format doesn't change the format of the current line; it creates a new paragraph, breaking the text at wherever your cursor was. 

The ugly:
- The text editor only takes up 2/3 of the screen (..?)
- Can't move files to different folders (!!)

### StackEdit

**4.5 / 5** 
The good:
- Instant preview!
	- Has a two-column structure: type on the left, see rendered output on the right
- Has most keyboard shortcuts (but not Cmd + K for links)
- Preserves unsaved content after refresh

The bad:
- Feels old
- No app
- 
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTExMDUyMzk2MiwyMTE0MzI3MTZdfQ==
-->