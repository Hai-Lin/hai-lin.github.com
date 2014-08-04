---
layout: post
title: Vi and janus
date: 2013-09-02 20:09:31
disqus: y
---


### CLI

One of the biggest advantages of Vi is it can run with (MacVim, GVim) or without a GUI, which matters a lot when you ssh into a remote machine. The other good thing about Vi  is that it kind of guaranteed that  you can find Vi on almost all \*unix like OS. Combining these two factors, Vi is the perfect tool when you ssh into a unknown remote machine just to modify a single line of a file. If you don't know a CLI editor which pre-installed on almost all \*unix system, you might end up with scp or X11 forwarding which normally is a painful experience. 

### Key bindings

Been using Vi heavily (basically for everything if possible), now I can't really use a text editor if I can't use <i>j</i> <i>k</i> to move up and down. Vi is the text editor for people so lazy to even move their fingers to the control key. Vi can be super powerful, but those power comes from the simplest design. It is a tool super optimize for jumping between lines and blocks with the smallest distance of finger movement on the keyboard. It allows you to type in a super fast way without even thinking about it.  I can type or edit much faster and better  if I learn a little bit of Vi. So, why not? 

### Configuration 

I use Vi for almost everything. For people like me, it is very likely
for us to install tons of Vi plug-ins to turn Vi into a IDE like full
featured super powerful text editor. I used to spend all day watching podcasts on   [Vim
cast](http://vimcasts.org/) and tried to search/install a fancy plug-in.
Until one day I find I got a tons of configuration/plug-ins, and it is
hard to setup everything perfectly I already have on a new environment ( new laptop, new VM). 
There are some tool that help you manager all you Vi plug-ins like
[vundle](https://github.com/gmarik/vundle) and
[pathogen](https://github.com/tpope/vim-pathogen). Even so,  I begin to miss
those days that I only have to keep a simple RC file to
config my personal key mapping. Then, I found Janus.

### Janus, A Vim distribution

Janus is a convention over
configuration like Vi distribution package. It goes with some very popular Vi
plug-ins, color-themes and key bindings. Janus have a .vimrc.before and .vimrc.after files
which allow you to put you own configuration before or after it got install. It's a open source project hosted
on [GitHub](https://github.com/carlhuda/janus), and now it got over 4000 stars, which means it won't disappear in a
week. Janus also provided a one line script installation, so you can move all the good things to any machine with a Internet connection in 5 minutes. You don't worry about
updating plug-ins, color themes, and put a huge configuration files on
a host any more. 
I know there are a bunch of people enjoy spending times
on configuration their text editors. 
I used to be one of them, but now I
realizes that Vi is one of the fastest, simplest text editor. So keep it
simple, light weighted as it should be. 
