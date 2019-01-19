---
layout: post
title: Looks like my domain name is now working with GitHub Pages (this site)
---

My custom domain is finally pointing to this site!
```
wcg-macbookpro:~ grisaitisw$ dig grisaitis.github.io +noall +answer

; <<>> DiG 9.8.3-P1 <<>> grisaitis.github.io +noall +answer
;; global options: +cmd
grisaitis.github.io.	2036	IN	A	185.199.108.153
grisaitis.github.io.	2036	IN	A	185.199.111.153
grisaitis.github.io.	2036	IN	A	185.199.109.153
grisaitis.github.io.	2036	IN	A	185.199.110.153
wcg-macbookpro:~ grisaitisw$ dig grisait.is +noall +answer

; <<>> DiG 9.8.3-P1 <<>> grisait.is +noall +answer
;; global options: +cmd
grisait.is.		46	IN	A	185.199.111.153
grisait.is.		46	IN	A	185.199.108.153
grisait.is.		46	IN	A	185.199.109.153
grisait.is.		46	IN	A	185.199.110.153
```

I use a funky domain registrar and administrator, [1984.is hosting](https://1984.is). My top level domain, `.is`, is Icelandic, and the most common registrars don't offer those domains. 

To make things work I:
* created 4 `A` entries, with `grisait.is` as the host pointing to each of the four IP addresses listed in [GitHub's help page on apex domains](https://help.github.com/articles/setting-up-an-apex-domain).
* created a `CNAME` entry for `www` pointing to `grisaitis.github.io`
  * i did _not_ edit the `./CNAME` file in the root directory of this repo, contrary to some other tutorials i've seen

I also found that GitHub pages stopped working after I renamed my GH repo name to `grisait.is`. So I had to reenable it in the repo settings.

Comment below if you're having issues with configuring your site and I'll do what I can to help. 
