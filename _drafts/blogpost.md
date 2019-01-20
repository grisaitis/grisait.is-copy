---
undefined: What's the best workflow for maintaining a GitHub Pages blog?
date: 2019-01-20 23:40:28 +0000

---
I love the simplicity of Jekyll and GitHub pages, but I'd like a nice interface for drafting posts. If I were God or the CEO of Google, I'd add a Google Docs plugin for publishing documents as blog posts. Short of any religious intervention, what's a dev blogger to do?

There are a few options for maintaining a Jekyll blog:

1. Do everything in GitHub - drafting, publishing, formatting, organizing sections, etc.
2. Draft posts in a content editor, but do everything else yourself. For example Prose.io is a markdown editor that syncs with Google Drive or your blog's GitHub repo.
3. Do everything through a CMS app like Forestry.io. This handles all of the above: drafting, publishing, formatting, organization, etc. And you basically never interact with GitHub or anything else.

In a nutshell, it depends on how much complexity you want to handle yourself versus rely on an external tool to execute for you.

I'm trying Forestry right now -- a la #3. The UI is nice, but the whole system is a little anxiety inducing. My basic concern is: can I safely "pop the hood" with Forestry and edit things manually if I want to? For example: if I draft a post in Forestry, can I edit it elsewhere and then access the modified version in Forestry? I don't know; it depends how Forestry saves drafts. (Does it save them to the `_drafts` folder in the repo? Probably not; that'd be a lot of git commits. But then how?) Anyway, I could answer this question, but I'd still have 100 other similar questions: modifying themes, plug-ins, formatting (LaTeX for math, anyone?), et cetera. 

Option 2 is probably the best: edit posts in a editor, and handle the other stuff yourself. But, which editor do you use? People on the internet (can they be trusted?) seem to recommend [dillinger.io](), [prose.io](), and [stackedit.io](). Are these the best? Or are people just fetishizing the `.io` top level domain? Luckily they look easy to try out. 

Option 1 -- let's call it "accessory reductionism" -- seems good as a start. I happily drafted and published my first posts directly on GitHub. It's great: it's simple and you get immediate feedback on whether and how the system works. But I realized quickly that I'd want some automation and help, mainly with formatting and templating markdown  files. 

The main things I want help with, in any tool, are:

* Saving drafts
* Formatting LaTeX in markdown files
* Handling Jekyll syntax in markdown files
* Any other markdown formatting or syntax esoterica

I'll check back later after I try out some editors. 

Happy blogging,

William