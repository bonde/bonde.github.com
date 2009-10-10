---
layout: post
title: My dotfiles
tags: [linux, vim, zsh, mutt]

---

I've finally pulled myself together and made a repository on GitHub with my
configuration files.  I've just doubled checked them for any personal info that
might have been and they're clean.

I've provided my `vimrc` which is a hybrid of my old config from Gentoo and
various elements from [ahf's vimrc](http://github.com/ahf/ahf-vim).  The
tab-completion is pure genius. Other than that I think it's pretty standard.

My long time `zshrc` is also in the repository.  It corrects typos :)  I have
yet to find out whether `zsh` correcting my typing errors is a good thing.
Probably not. This config also keeps me cheered up as it run `fortune` whenever
it is sourced.

Finally there's my mutt configuration files.  I just recently started using mutt
as I really needed something that could provide different profiles depending on
the receiver.  Gmail's interface, though pretty neat, just didn't cut it. I
found a reasonable solution by sourcing different files with headers and
signatures by using folder hooks.  It gets the job done and it sorta work :)
Anyways, here's the repository:
[http://github.com/bonde/dotfiles](http://github.com/bonde/dotfiles).

<!-- vim: set tw=80 ft=mkd sw=4 sts=4 et : -->
