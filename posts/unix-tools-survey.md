---
title: Unix utilities you should know and love
date: '2012-06-28'
description:
tags: ['workflow', 'UNIX']
---

This post is a brief survey of a number of plugins and utilities I
use, in order of descending usage.

1. [TMUX](http://tmux.sourceforge.net/) - If you haven't given this
one a try, or you're still using screen, I highly recommend you try
it out. It plays very nicely with VIM too (think Slime for Gnu
Screen). Plus, it's scriptable and configurable.

2. [EMACS](http://www.gnu.org/software/emacs/) - Yes, yes, you're a
hardcore VIM user, and I don't blame you! I love VIM too. That's why I
use the
[Evil](http://dnquark.com/blog/2012/02/emacs-evil-ecumenicalism/)
EMACS plugin and turn on VIM's normal mode by default. Why EMACS and
not just VIM you ask? Indentation, that's why! After hacking in
Haskell for a long time, and now Erlang, the last thing I want to have
to manage are indentation levels. With EMACS/Evil, I get the both of
both worlds. I map <jk> to the VIM escape mode so it doesn't conflict
with EMACS usage of the escape key as the Meta key. I also map <jj> to
'insert j' in case I *do*, in fact, need to type a j quickly at some
point in time.

3. [xmonad](http://xmonad.org/) - Also in line with saving brain
cycles to do real work, I use xmonad so I never really have to *think*
about where my windows are or how to size them. It just _happens_. You
can configure xmonad to open specific locations on specific desktops,
and even configure the sizes of individual panes and such. Best of
all, navigating through panes uses default VIM cursor movement
motions.

4. [Zsh](http://www.zsh.org/) - Zsh is a polarizing topic and strikes
a chord with many BASh enthusiasts. Personally, I find Zsh's file
globbing, smart autocompletion, and more sensible scripting syntax too
good to pass up. Plug in Robby Russel's
[oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) for snazzy
additions like git branch autocompletion, sensible aliases, and more.

5. [SOLARIZED](http://ethanschoonover.com/solarized) - OK, not a
plugin but great nonetheless. If you're going to spend the majority of
your time staring at a terminal, the least you could do is make it
pretty. Feel free to tack on
[zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/) 
while you're at it.

6. [htop](http://htop.sourceforge.net/) - If you do frequent
benchmarking, learn htop over top. Has convenient features like
killing processes by name instead of PID, visual core and memory usage
bars, and more.

7. [irssi](http://www.irssi.org/) - A hacker's favorite IRC client. If
you aren't already constantly lurking or participating in a relevant
IRC channel, you're probably missing out on a ton of knowledge and
interaction with very, very knowledgeable people. Try #math, #physics, #haskell, #erlang, #emacs, #vim, and more on freenode.
